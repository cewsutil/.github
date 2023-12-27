[Certificate Enrollment Web Services (CEWS)](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/hh831822(v=ws.11)) is a suite of Microsoft protocols for interacting
with a Microsoft [Active Directory Certificate Services (ADCS)](https://learn.microsoft.com/en-us/windows-server/identity/ad-cs/active-directory-certificate-services-overview)
[Certification Authority (CA)](https://learn.microsoft.com/en-us/windows-server/identity/ad-cs/certification-authority-role) which uses [SOAP](https://en.wikipedia.org/wiki/SOAP) instead of
[DCOM](https://en.wikipedia.org/wiki/Distributed_Component_Object_Model).

__cewsutil__ is a project consisting of a library and utility to interact with a CEWS installation in order to retrieve certificate profiles and to enrol for certificates.

It's main purpose is to allow non-Windows systems to ernol for certificates from a Microsoft ADCS CA.
