# Instalujemy PacketTracer w systemie Arch Linux 


Nim zaczniesz, upewnij się, że posiadasz w systemie następujące zależności:

* icu52

* libpng12

* openssl-1.0

Wszystkie z nich znajdziesz w AUR (Arch User Repository).

1. Pobieramy PKGBUILD z AUR bądź z Githuba

* AUR

```
git clone https://aur.archlinux.org/packettracer.git

```
* Github

```
git clone https://github.com/WSEI-2015-Team/ask.git

```

2. Zakładamy konto Cisco:

https://www.netacad.com/campaign/ptdt-4

3. Pobieramy PacketTracer

https://www.netacad.com/group/offerings/all-resources/-/document_library_display/PKecjqM38xNC/view/922864?_110_INSTANCE_PKecjqM38xNC_redirect=http%3A%2F%2Fwww.netacad.com%2Fgroup%2Fofferings%2Fall-resources%3Fp_p_id%3D110_INSTANCE_PKecjqM38xNC%26p_p_lifecycle%3D0%26p_p_state%3Dnormal%26p_p_mode%3Dview%26p_p_col_id%3Dcolumn-2%26p_p_col_count%3D1

4. Instalujemy

Przechodzimy do katalogu w którym pobraliśmy źródła:

* AUR

```
cd packetrracer
makepkg -ci

```
* Github

```
cd PacketTracer/ArchLinux
makepkg -ci

```

## UWAGA!

Oczywiście przed wykonaniem polecenia makepkg musimy umieścić pobrane źródła w katalogu packetrracer!!!

Jest to natywny Linuksowy pakiet niewymagający wine. 


<p align="center">
  <img src="https://s1.postimg.org/30uzz233of/cisco_packet_tracer_linux.png" alt="cistopt"/>
</p>



