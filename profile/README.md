### Hardened Distroless container images with a distro-like experience
_Enterprise-grade golden base container images_




![Koala_Video](https://github.com/user-attachments/assets/d20795dc-716c-4722-9feb-0b866d3afb7e)






KoalaLab's mission to help the world use open-source software in a secure manner. 90% of all modern software is open-source but that comes with it's own security risks.

One of the lowest hanging fruits is moving to "Hardened base container images" as the VM->container era transition led to bloated containers with excessive packages leading to both a. Larger attack surface and b. subpar performance. But enterprises have not been able to move to hardened base images because developers are unfamiliar with a newer(or non-existent toolchain)

KoalaLab is building "Secure OSS container images for everyone" aka _golden images_. 
Koala's distro: 0-deb, *a container-first debian-inspired linux*, allows for creation of hardened container images which follow distroless security philosophy while providing familiar exeprience for developers.
