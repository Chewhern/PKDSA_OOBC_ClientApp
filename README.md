# PKDSA_OOBC_ClientApp

1. **This application relies on .Net 7.0 and AvaloniaUI.**
2. **Kindly use visual studio or any other applicable IDE to do "dotnet build" on PKDSA_OOBC_ClientApp.csproj and PKDSA_OOBC_ClientApp.Desktop.csproj.**
3. **Search for the compiled application within "PKDSA_OOBC_ClientApp.Desktop/bin/debug/net7.0" folder**.

Newer version of PKDSA uses out of band communication and web of trust to do trust validation and verification (Will upload in GitHub if have time).

In theory, out of band communication combined with web of trust and net neutrality with a prerequisite of not forgetting the out of band digital signature key pair.

They have 2 benefits described below.
1. Bypassing any form of service blockage such as the blocking of Russia software engineers from commiting to any github repositories since the most recent Russia-Ukraine conflict.
2. Allowing flexible account registration and authentication that no longer rely on company's preregistered email or personal email because the first company can delete the email which blocks all the access to any account associated and the latter can be locked out if the email owner forgets their passwords.

They have several cons.
1. It'll be very inconvenient for users.
2. It'll now rely on offline security.
3. This kind of method can not be automated. 
