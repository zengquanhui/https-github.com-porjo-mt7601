# https-github.com-porjo-mt7601
pkgbase = dkms-mt7601
	pkgdesc = Driver for Ralink MT7601 chipset wireless adaptors
	pkgver = v3.0.0.4
	arch = x86_64
	license = GPL
	depends = dkms
	depends = linux-headers
	source = git://github.com/davex25/mt7601
	source = dkms.conf
	options = !strip

pkgname = dkms-mt7601
