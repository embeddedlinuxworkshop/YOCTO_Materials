

```bash 
do_fetch(){
	# fetch from SRC_URI.
}

do_patch (){
	# apply patch on source code.
}


do_configure(){
	# apply configuration on source code.
}


do_compile(){
	# --- compile source code. ---
	# --- ${CC} OR ${CXX}. ---
}


do_install(){
	# install files from {$WORKDIR} ----> source directory to for example ${bindir}.
}

do_install() { 
	install -d ${D}${bindir} 
	install -m 0755 hello ${D}${bindir} 
}

```