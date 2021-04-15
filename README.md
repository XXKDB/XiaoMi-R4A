
来自这位大佬：https://github.com/YL2209/Actions-OpenWrt-Xiaomi-R4A


魔改成了 使用 Lean 大佬的 https://github.com/coolsnowwolf/lede openwrt源码编译 小米R4A千兆版 的 breed直刷版

 .yml文件中修改 openwrt源码，使其能 breed 直刷 （参考pidge 提供的方法 分享小米R4A千兆版编译OPENWRT(Breed直刷版) 修改，编译生成的固件就可以用breed直刷了）

mv mt7621.mk openwrt/target/linux/ramips/image/mt7621.mk
mv mt7621_xiaomi_mir3g-v2.dts openwrt/target/linux/ramips/dts/mt7621_xiaomi_mir3g-v2.dts

根目录 放置mt7621.mk和mt7621_xiaomi_mir3g-v2.dts文件

