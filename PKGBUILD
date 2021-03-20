# AArch64 multi-platform
# Maintainer: Dan Johansen <strit@manjaro.org>
# Contributor: Kevin Mihelich <kevin@archlinuxarm.org>

pkgbase=linux
_srcname=linux-5.11
_kernelname=${pkgbase#linux}
_desc="AArch64 multi-platform"
pkgver=5.11.8
pkgrel=1
arch=('aarch64')
url="http://www.kernel.org/"
license=('GPL2')
makedepends=('xmlto' 'docbook-xsl' 'kmod' 'inetutils' 'bc' 'git' 'uboot-tools' 'dtc')
options=('!strip')
source=("http://www.kernel.org/pub/linux/kernel/v5.x/${_srcname}.tar.xz"
        "http://www.kernel.org/pub/linux/kernel/v5.x/patch-${pkgver}.xz"
        '0001-net-smsc95xx-Allow-mac-address-to-be-set-as-a-parame.patch'
        '0002-arm64-dts-rockchip-add-usb3-controller-node-for-RK33.patch'
        '0003-arm64-dts-rockchip-enable-usb3-nodes-on-rk3328-rock6.patch'
        '0004-arm64-dts-rockchip-add-HDMI-sound-node-for-rk3328-ro.patch'
        '0005-arm64-dts-allwinner-add-hdmi-sound-to-pine-devices.patch'
        '0006-arm64-dts-allwinner-add-ohci-ehci-to-h5-nanopi.patch'
        '0007-drm-bridge-analogix_dp-Add-enable_psr-param.patch'
        '0008-gpu-drm-add-new-display-resolution-2560x1440.patch'
        '0009-nuumio-panfrost-Silence-Panfrost-gem-shrinker-loggin.patch'
        '0010-arm64-dts-rockchip-Add-Firefly-Station-p1-support.patch'
        '0011-typec-displayport-some-devices-have-pin-assignments-reversed.patch'
        '0012-usb-typec-tcpm-Add-generic-extcon-for-tcpm-enabled-devices.patch'
        '0013-usb-typec-tcpm-Add-generic-extcon-to-tcpm.patch'
        '0014-arm64-rockchip-add-DP-ALT-rockpro64.patch'
        '0015-ayufan-drm-rockchip-add-support-for-modeline-32MHz-e.patch'
        '0016-rk3399-rp64-pcie-Reimplement-rockchip-PCIe-bus-scan-delay.patch'
        '0017-tty-serdev-support-shutdown-op.patch'
        '0018-bluetooth-hci_serdev-Clear-registered-bit-on-unregister.patch'
        '0019-bluetooth-hci_bcm-disable-power-on-shutdown.patch'
        '0020-mmc-core-pwrseq_simple-disable-mmc-power-on-shutdown.patch'
        '0021-usb-typec-bus-Catch-crash-due-to-partner-NULL-value.patch'
        '0022-phy-rockchip-typec-Set-extcon-capabilities.patch'
        '0023-usb-typec-altmodes-displayport-Add-hacky-generic-altmode.patch'
        '0024-sound-soc-codecs-es8316-Run-micdetect-only-if-jack-status.patch'
        '0025-ASoC-soc-jack.c-supported-inverted-jack-detect-GPIOs.patch'
        '0026-arm64-dts-rockchip-add-typec-extcon-hack.patch'
        '0027-arm64-dts-rockchip-setup-USB-type-c-port-as-dual-data-role.patch'
        '0028-revert-arm64-dts-allwinner-a64-Add-I2S2-node.patch'
        '0001-Bluetooth-Add-new-quirk-for-broken-local-ext-features.patch'
        '0002-Bluetooth-btrtl-add-support-for-the-RTL8723CS.patch'
        '0003-arm64-allwinner-a64-enable-Bluetooth-On-Pinebook.patch'
        '0004-arm64-dts-allwinner-enable-bluetooth-pinetab-pinepho.patch'
        '0005-dt-bindings-arm-sunxi-add-PineTab-Early-Adopter-edition.patch'
        '0006-staging-add-rtl8723cs-driver.patch'
        '0001-revert-fbcon-remove-now-unusued-softback_lines-cursor-argument.patch'
        '0002-revert-fbcon-remove-no-op-fbcon_set_origin.patch'
        '0003-revert-fbcon-remove-soft-scrollback-code.patch'
        '0001-bootsplash.patch'
        '0002-bootsplash.patch'
        '0003-bootsplash.patch'
        '0004-bootsplash.patch'
        '0005-bootsplash.patch'
        '0006-bootsplash.patch'
        '0007-bootsplash.patch'
        '0008-bootsplash.patch'
        '0009-bootsplash.patch'
        '0010-bootsplash.patch'
        '0011-bootsplash.patch'
        '0012-bootsplash.patch'
        'config'
        'linux.preset'
        '60-linux.hook'
        '90-linux.hook'
        'add-beelink-device-and-vim3l.patch'
        'add-ugoos-device.patch'
        'fix-g12-hdmi.patch')
md5sums=('d2985a3f16ef1ea3405c04c406e29dcc'
         'b7a8f78992a38c966a8ea00ad8cbd451'
         '9e6b7f44db105fef525d715213dce7cf'
         '9986e28b5c2c3c62a5c3bb53abd94640'
         '552ea82c3a5e14ca9149da8c4b4d5a82'
         '345e1329e2b6a530554d8538415caebe'
         'fa586447846ec5aef8ab972058c5548e'
         'e6fe272dc95a1c0a8f871924699fea16'
         '9f27b2a05eaeb1995fc0fcf6a8b923c4'
         '6f592c11f6adc1de0f06e5d18f8c2862'
         'f8f0b124c741be61d86bea8d44e875f9'
         '073296b5eba7daf6d707c21abbfc49ce'
         'a033be22c23afb1d5daeeeb21353185d'
         '6a88f7e762eb7895b3f5db38daa6bb24'
         'e78fd8f59f5d073069aec121e033590b'
         '09fc19ac5c51e2839ca56248ccf6323a'
         '66fae3fc96f0a478a56ff11632f3ef70'
         '245858f26512dfc48adbf509b6fc8364'
         'b3875d0253b8018af15af9512ed94962'
         '46d365b674920f85637a9d7865781f87'
         '817f321b4bc9d075a0ec72eefaafa113'
         '19d836fc7c463011b696640a193b842f'
         '005e92dfe1cb92062b7abf3e7ef9a208'
         '252b4dbd2d0f560b6d254f29dd5b0f5f'
         'ab9c0c25e2b7272fca3caf491b7dc89c'
         'bd0d0667d2fdac9b1566dd906775975d'
         '0eb00bfcc68cae984bfdbbca6409e2a6'
         'c706ccdf118f4146e7ca35808d819b8a'
         'bb500ee93275583d5ba3d11842e09735'
         'e89d3ca6ae8ae8f3eb8168cacaefb9e0'
         'cf64831f27bb47da29e708b7243bb340'
         'e3f53e07612939729afaa4dd7ef7f7ce'
         '9510821113c122f91f47b9d0f7ca7264'
         'a74fcfa1e085a3a99dcf4f214c1ca65a'
         '418db11ca0cf3454333db1ad9a338337'
         'b0fa7d19514a8bd351ebf00564b2094e'
         '2496e6fc16f67b289f72ddc2ea2511cf'
         'fed6ae4ac4c3f56178fa4aca6c934d6f'
         '47f65423c4ffc7e6092c7ff2c7129942'
         'be5a873f638ff5c31947f8d28a824d3a'
         'b4acd66a564af83b5409738c40b4a566'
         'a6407dceae1838f5aa27450401a91be6'
         'cb78b1c11b917a4d31c4b1567183b76f'
         '3efea575da7f02ba94789d3b6b81e11f'
         '2529ad13791b259d80c9d5d702187a65'
         'cb296d7788098cf478c46c0d21376719'
         '50255aac36e002afa477e4527a0550af'
         '6b6def41b404422dc04b39e2f1adffc8'
         '1922e3a7727d2bf51641b98d6d354738'
         'd6b7e4e43e42128cf950251e0d0aee23'
         'ecfd8a30c480149005fcf349e4d06f4b'
         'efa97e822bf22301de560e5f44a1fa62'
         '86d4a35722b5410e3b29fc92dae15d4b'
         'ce6c81ad1ad1f8b333fd6077d47abdaf'
         '3dc88030a8f2f5a5f97266d99b149f77'
         'f77a1334c2a70334c990cc6e412ee849'
         '1b92d7617e60d3c525a4b18ab4351185'
         '469417b64e6a2bf65bd74c6d9cad2040')

prepare() {
  cd ${_srcname}

  # add upstream patch
  patch -Np1 -i "${srcdir}/patch-${pkgver}"

  # ALARM patches
  patch -Np1 -i "${srcdir}/0001-net-smsc95xx-Allow-mac-address-to-be-set-as-a-parame.patch"             #All
  patch -Np1 -i "${srcdir}/0002-arm64-dts-rockchip-add-usb3-controller-node-for-RK33.patch"             #RK3328
  patch -Np1 -i "${srcdir}/0003-arm64-dts-rockchip-enable-usb3-nodes-on-rk3328-rock6.patch"             #RK3328
  
  # Manjaro ARM Patches
  patch -Np1 -i "${srcdir}/0004-arm64-dts-rockchip-add-HDMI-sound-node-for-rk3328-ro.patch"             #Rock64
  patch -Np1 -i "${srcdir}/0005-arm64-dts-allwinner-add-hdmi-sound-to-pine-devices.patch"               #Pine64
  patch -Np1 -i "${srcdir}/0006-arm64-dts-allwinner-add-ohci-ehci-to-h5-nanopi.patch"                   #Nanopi Neo Plus 2
  patch -Np1 -i "${srcdir}/0007-drm-bridge-analogix_dp-Add-enable_psr-param.patch"                      #Pinebook Pro
  patch -Np1 -i "${srcdir}/0008-gpu-drm-add-new-display-resolution-2560x1440.patch"             		#Odroid
  patch -Np1 -i "${srcdir}/0009-nuumio-panfrost-Silence-Panfrost-gem-shrinker-loggin.patch"             #Panfrost
  patch -Np1 -i "${srcdir}/0010-arm64-dts-rockchip-Add-Firefly-Station-p1-support.patch"                #Firelfy Station P1
  patch -Np1 -i "${srcdir}/0011-typec-displayport-some-devices-have-pin-assignments-reversed.patch"     #DP Alt Mode
  patch -Np1 -i "${srcdir}/0012-usb-typec-tcpm-Add-generic-extcon-for-tcpm-enabled-devices.patch"       #DP Alt mode
  patch -Np1 -i "${srcdir}/0013-usb-typec-tcpm-Add-generic-extcon-to-tcpm.patch"						#DP Alt mode
  patch -Np1 -i "${srcdir}/0014-arm64-rockchip-add-DP-ALT-rockpro64.patch"							    #DP Alt mode - RockPro64
  patch -Np1 -i "${srcdir}/0015-ayufan-drm-rockchip-add-support-for-modeline-32MHz-e.patch"             #DP Alt mode
  patch -Np1 -i "${srcdir}/0016-rk3399-rp64-pcie-Reimplement-rockchip-PCIe-bus-scan-delay.patch"        #RockPro64
  
  # Pinebook Pro patches
  patch -Np1 -i "${srcdir}/0017-tty-serdev-support-shutdown-op.patch"                                   #Wifi/BT
  patch -Np1 -i "${srcdir}/0018-bluetooth-hci_serdev-Clear-registered-bit-on-unregister.patch"          #Bluetooth
  patch -Np1 -i "${srcdir}/0019-bluetooth-hci_bcm-disable-power-on-shutdown.patch"                      #Bluetooth
  patch -Np1 -i "${srcdir}/0020-mmc-core-pwrseq_simple-disable-mmc-power-on-shutdown.patch"             #Wifi
  patch -Np1 -i "${srcdir}/0021-usb-typec-bus-Catch-crash-due-to-partner-NULL-value.patch"              #USB-C
  patch -Np1 -i "${srcdir}/0022-phy-rockchip-typec-Set-extcon-capabilities.patch"                       #DP Alt mode
  patch -Np1 -i "${srcdir}/0023-usb-typec-altmodes-displayport-Add-hacky-generic-altmode.patch"         #DP Alt mode
  patch -Np1 -i "${srcdir}/0024-sound-soc-codecs-es8316-Run-micdetect-only-if-jack-status.patch"        #Audio
  patch -Np1 -i "${srcdir}/0025-ASoC-soc-jack.c-supported-inverted-jack-detect-GPIOs.patch"             #Audio
  patch -Np1 -i "${srcdir}/0026-arm64-dts-rockchip-add-typec-extcon-hack.patch"                         #DP Alt mode
  patch -Np1 -i "${srcdir}/0027-arm64-dts-rockchip-setup-USB-type-c-port-as-dual-data-role.patch"       #USB-C charging
  
  # Pinebook, PinePhone and PineTab patches
  patch -Np1 -i "${srcdir}/0028-revert-arm64-dts-allwinner-a64-Add-I2S2-node.patch"                     #Allwinner
  patch -Np1 -i "${srcdir}/0001-Bluetooth-Add-new-quirk-for-broken-local-ext-features.patch"            #Bluetooth
  patch -Np1 -i "${srcdir}/0002-Bluetooth-btrtl-add-support-for-the-RTL8723CS.patch"                    #Bluetooth
  patch -Np1 -i "${srcdir}/0003-arm64-allwinner-a64-enable-Bluetooth-On-Pinebook.patch"                 #Bluetooth
  patch -Np1 -i "${srcdir}/0004-arm64-dts-allwinner-enable-bluetooth-pinetab-pinepho.patch"             #Bluetooth on PineTab and PinePhone
  patch -Np1 -i "${srcdir}/0005-dt-bindings-arm-sunxi-add-PineTab-Early-Adopter-edition.patch"          #PineTab screen
  patch -Np1 -i "${srcdir}/0006-staging-add-rtl8723cs-driver.patch"                                     #Wifi

  # Amlogic Patches
  patch -Np1 -i "${srcdir}/add-beelink-device-and-vim3l.patch"                                          # Beelink GT1 Ultimate
  patch -Np1 -i "${srcdir}/add-ugoos-device.patch"                                                      # Add Ugoos AM6 Plus
  patch -Np1 -i "${srcdir}/fix-g12-hdmi.patch"                                                          # Amglogic G12 Green Line fix    
  
  # Bootsplash patches
  patch -Np1 -i "${srcdir}/0001-revert-fbcon-remove-now-unusued-softback_lines-cursor-argument.patch"
  patch -Np1 -i "${srcdir}/0002-revert-fbcon-remove-no-op-fbcon_set_origin.patch"
  patch -Np1 -i "${srcdir}/0003-revert-fbcon-remove-soft-scrollback-code.patch"
  patch -Np1 -i "${srcdir}/0001-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0002-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0003-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0004-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0005-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0006-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0007-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0008-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0009-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0010-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0011-bootsplash.patch"
  patch -Np1 -i "${srcdir}/0012-bootsplash.patch"
  
  cat "${srcdir}/config" > ./.config

  # add pkgrel to extraversion
  sed -ri "s|^(EXTRAVERSION =)(.*)|\1 \2-${pkgrel}|" Makefile

  # don't run depmod on 'make install'. We'll do this ourselves in packaging
  sed -i '2iexit 0' scripts/depmod.sh
}

build() {
  cd ${_srcname}

  # get kernel version
  make prepare

  # load configuration
  # Configure the kernel. Replace the line below with one of your choice.
  #make menuconfig # CLI menu for configuration
  #make nconfig # new CLI menu for configuration
  #make xconfig # X-based configuration
  #make oldconfig # using old config from previous kernel version
  # ... or manually edit .config

  # Copy back our configuration (use with new kernel version)
  #cp ./.config /var/tmp/${pkgbase}.config

  ####################
  # stop here
  # this is useful to configure the kernel
  #msg "Stopping build"
  #return 1
  ####################

  #yes "" | make config

  # build!
  unset LDFLAGS
  make ${MAKEFLAGS} Image modules
  # Generate device tree blobs with symbols to support applying device tree overlays in U-Boot
  make ${MAKEFLAGS} DTC_FLAGS="-@" dtbs
}

_package() {
  pkgdesc="The Linux Kernel and modules - ${_desc}"
  depends=('coreutils' 'linux-firmware' 'kmod' 'mkinitcpio>=0.7')
  optdepends=('crda: to set the correct wireless channels of your country')
  provides=('kernel26' "linux=${pkgver}")
  conflicts=('kernel26' 'linux')
  replaces=('linux-armv8' 'linux-aarch64')
  backup=("etc/mkinitcpio.d/${pkgbase}.preset")
  install=${pkgname}.install

  cd ${_srcname}

  KARCH=arm64

  # get kernel version
  _kernver="$(make kernelrelease)"
  _basekernel=${_kernver%%-*}
  _basekernel=${_basekernel%.*}

  mkdir -p "${pkgdir}"/{boot,usr/lib/modules}
  make INSTALL_MOD_PATH="${pkgdir}/usr" modules_install
  make INSTALL_DTBS_PATH="${pkgdir}/boot/dtbs" dtbs_install
  cp arch/$KARCH/boot/Image "${pkgdir}/boot"

  # make room for external modules
  local _extramodules="extramodules-${_basekernel}${_kernelname}"
  ln -s "../${_extramodules}" "${pkgdir}/usr/lib/modules/${_kernver}/extramodules"

  # add real version for building modules and running depmod from hook
  echo "${_kernver}" |
    install -Dm644 /dev/stdin "${pkgdir}/usr/lib/modules/${_extramodules}/version"

  # remove build and source links
  rm "${pkgdir}"/usr/lib/modules/${_kernver}/{source,build}

  # now we call depmod...
  depmod -b "${pkgdir}/usr" -F System.map "${_kernver}"

  # add vmlinux
  install -Dt "${pkgdir}/usr/lib/modules/${_kernver}/build" -m644 vmlinux

  # sed expression for following substitutions
  local _subst="
    s|%PKGBASE%|${pkgbase}|g
    s|%KERNVER%|${_kernver}|g
    s|%EXTRAMODULES%|${_extramodules}|g
  "

  # install mkinitcpio preset file
  sed "${_subst}" ../linux.preset |
    install -Dm644 /dev/stdin "${pkgdir}/etc/mkinitcpio.d/${pkgbase}.preset"

  # install pacman hooks
  sed "${_subst}" ../60-linux.hook |
    install -Dm644 /dev/stdin "${pkgdir}/usr/share/libalpm/hooks/60-${pkgbase}.hook"
  sed "${_subst}" ../90-linux.hook |
    install -Dm644 /dev/stdin "${pkgdir}/usr/share/libalpm/hooks/90-${pkgbase}.hook"
}

_package-headers() {
  pkgdesc="Header files and scripts for building modules for linux kernel - ${_desc}"
  provides=("linux-headers=${pkgver}")
  conflicts=('linux-headers')
  replaces=('linux-aarch64-headers')

  cd ${_srcname}
  local _builddir="${pkgdir}/usr/lib/modules/${_kernver}/build"

  install -Dt "${_builddir}" -m644 Makefile .config Module.symvers
  install -Dt "${_builddir}/kernel" -m644 kernel/Makefile

  mkdir "${_builddir}/.tmp_versions"

  cp -t "${_builddir}" -a include scripts

  install -Dt "${_builddir}/arch/${KARCH}" -m644 arch/${KARCH}/Makefile
  install -Dt "${_builddir}/arch/${KARCH}/kernel" -m644 arch/${KARCH}/kernel/asm-offsets.s

  cp -t "${_builddir}/arch/${KARCH}" -a arch/${KARCH}/include
  mkdir -p "${_builddir}/arch/arm"
  cp -t "${_builddir}/arch/arm" -a arch/arm/include

  install -Dt "${_builddir}/drivers/md" -m644 drivers/md/*.h
  install -Dt "${_builddir}/net/mac80211" -m644 net/mac80211/*.h

  # http://bugs.archlinux.org/task/13146
  install -Dt "${_builddir}/drivers/media/i2c" -m644 drivers/media/i2c/msp3400-driver.h

  # http://bugs.archlinux.org/task/20402
  install -Dt "${_builddir}/drivers/media/usb/dvb-usb" -m644 drivers/media/usb/dvb-usb/*.h
  install -Dt "${_builddir}/drivers/media/dvb-frontends" -m644 drivers/media/dvb-frontends/*.h
  install -Dt "${_builddir}/drivers/media/tuners" -m644 drivers/media/tuners/*.h

  # add xfs and shmem for aufs building
  mkdir -p "${_builddir}"/{fs/xfs,mm}

  # copy in Kconfig files
  find . -name Kconfig\* -exec install -Dm644 {} "${_builddir}/{}" \;

  # remove unneeded architectures
  local _arch
  for _arch in "${_builddir}"/arch/*/; do
    [[ ${_arch} == */${KARCH}/ || ${_arch} == */arm/ ]] && continue
    rm -r "${_arch}"
  done

  # remove files already in linux-docs package
  rm -r "${_builddir}/Documentation"

  # remove now broken symlinks
  find -L "${_builddir}" -type l -printf 'Removing %P\n' -delete

  # Fix permissions
  chmod -R u=rwX,go=rX "${_builddir}"

  # strip scripts directory
  local _binary _strip
  while read -rd '' _binary; do
    case "$(file -bi "${_binary}")" in
      *application/x-sharedlib*)  _strip="${STRIP_SHARED}"   ;; # Libraries (.so)
      *application/x-archive*)    _strip="${STRIP_STATIC}"   ;; # Libraries (.a)
      *application/x-executable*) _strip="${STRIP_BINARIES}" ;; # Binaries
      *) continue ;;
    esac
    /usr/bin/strip ${_strip} "${_binary}"
  done < <(find "${_builddir}/scripts" -type f -perm -u+w -print0 2>/dev/null)
}

pkgname=("${pkgbase}" "${pkgbase}-headers")
for _p in ${pkgname[@]}; do
  eval "package_${_p}() {
    _package${_p#${pkgbase}}
  }"
done
