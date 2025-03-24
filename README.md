# deploy_database_ansible
deploy service for ansible


# done

- tar: glibc pcre attr libselinux libacl
- zlib: glibc
- attr: glibc
- gawk: glibc readline ncurses-libs
- grep: glibc pcre
- findutils: glibc pcre selinux
- sed: glibc pcre selinux
- patch: glibc pcre selinux attr
- vim: glibc pcre selinux attr acl ncurses-libs
- less: glibc ncurses-libs
- diffutils: glibc
- inetutils:
- iproute2:
- readline: glibc ncurses-libs
- openssl: glibc
- libgpg-error: glibc
- libgcrypt: glibc libgpg-error
- bison: glibc
- gmp: glibc
- mpfr: glibc gmp
- mpc: glibc gmp mpfr
- isl: glibc gmp
- gcc: glibc(libm libc libdl libpthread) gmp mpfr mpc isl zlib zstd
- m4:
- libunistring:
- gettext:依赖gcc版本、libunistring、libpthread、libacl、libattr、libm、libc、libncurses、ncurses-libs、libdl、libgomp
  - libgettextlib-0.21.so
  - libgettextsrc-0.21.so
  - libtextstyle.so.0.1.1
- tcl: libz glibc
- libtirpc: glibc libselinux pcre keyutils-libs libcom_err krb5-libs







####  zlib < tcl




# not done
- grub:gcc 5.1 or newer or clang 8.0 or newer,依赖gcc版本
- util-linux:
- expat









