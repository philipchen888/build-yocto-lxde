apply_patches:
	cd poky/build; \
	rm -f ../meta-radxa/recipes-kernel/cypress-backports/brcmfmac.bb; \
	cp ../../patches/linux-rockpi-4_4.4.bb ../meta-radxa/recipes-kernel/linux/; \
	cp -r ../../patches/recipes-graphics ../meta-radxa/; \
	cp ../../patches/modify.patch ../meta-radxa/recipes-bsp/u-boot/files/; \
	cp ../../patches/u-boot-rockchip.bb ../meta-radxa/recipes-bsp/u-boot/; \
	cp ../../patches/rockpi-4b-rk3399.conf ../meta-radxa/conf/machine/; \
	cp ../../patches/lxsession_0.5.4.bb ../meta-lxde/recipes-lxde/lxsession/; \
	cp ../../patches/bblayers.conf ./conf/; \
	cp ../../patches/local.conf ./conf/
