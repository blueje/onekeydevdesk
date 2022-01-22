
          ## az
          #sudo sed -i "s/export[[:space:]]tmpINSTSSHONLY='0'/export tmpINSTSSHONLY='1'/g" ./ci.sh
          #sudo sed -i "s/gitee.com\/minlearn\/onekeydevdesk/github.com\/minlearn\/onekeydevdeskaz/g" ./ci.sh
          #sudo sed -i "s/_build\/onekeydevdesk/_build\/onekeydevdeskaz/g" ./ci.sh
          #sudo sed -i "/INSERT INTO tree VALUES(10,0,10,0,1627330418,4,'priv',NULL);/a xxx" ./p/300.1keydd/ci2.sh
          #sudo chmod +x ./ci.sh && sudo ./ci.sh -b 0 -h 0 -t onekeydevdesk

          ## ks
          #sudo sed -i "s/export[[:space:]]tmpBUILDGENE='0'/export tmpBUILDGENE='1'/g" ./ci.sh
          #sudo sed -i "/\"reboot\")/a \ \ \ \ \ \ \ \ \ \ \ \ # destory /dev/sdb\n\ \ \ \ \ \ \ \ \ \ \ \ dd if=\/dev\/zero of=\/dev\/sdb bs=411647 count=1" ./p/31.remaster/ci2.sh
          #sudo sed -i "/copy_including_deps[[:space:]]\$LMK\/kernel\/drivers\/net\/virtio_net.ko/a \ \ copy_including_deps \$LMK\/kernel\/drivers\/net\/ethernet\/intel\/igb\/igb.ko\n\ \ copy_including_deps \$LMK\/kernel\/drivers\/net\/ethernet\/intel\/e1000e\/e1000e.ko" ./p/31.remaster/ci2.sh
          #sudo sed -i "s/gitee.com\/minlearn\/onekeydevdesk/github.com\/minlearn\/onekeydevdeskks/g" ./ci.sh
          #sudo sed -i "s/_build\/onekeydevdesk/_build\/onekeydevdeskks/g" ./ci.sh
          #sudo chmod +x ./ci.sh && sudo ./ci.sh -b 0 -h 0 -t onekeydevdesk

          ## orc
          #sudo sed -i "s/export[[:space:]]tmpBUILDGENE='0'/export tmpBUILDGENE='1'/g" ./ci.sh
          #sudo sed -i "s/gitee.com\/minlearn\/onekeydevdesk/github.com\/minlearn\/onekeydevdeskorc/g" ./ci.sh
          #sudo sed -i "s/_build\/onekeydevdesk/_build\/onekeydevdeskorc/g" ./ci.sh
          #sudo sed -i "s/remasteringdir\/grub2\/boot\/grub\/grub.cfg/remasteringdir\/grub2\/efi\/boot\/grub.cfg/g" ./p/31.remaster/ci2.sh
          #sudo sed -i "s/\[\[ \"\$tmpBUILDGENE\"[[:space:]]==[[:space:]]'1'[[:space:]]\]\][[:space:]]\&\&[[:space:]]cp/# \[\[ \"\$tmpBUILDGENE\" == '1' \]\] \&\& cp/g" ci.sh
          #sudo chmod +x ./ci.sh && sudo ./ci.sh -b 0 -h 0 -t onekeydevdesk

          ## spt15g
          #sudo sed -i "s/export[[:space:]]custIMGSIZE='20'/export custIMGSIZE='15'/g" ./ci.sh
          #sudo sed -i "s/imgsizeinfo=\$TARGETDDIMGSIZE/imgsizeinfo='15'/g" ./p/31.remaster/ci2.sh
          #sudo sed -i "s/gitee.com\/minlearn\/onekeydevdesk/github.com\/minlearn\/onekeydevdeskspt15g/g" ./ci.sh
          #sudo sed -i "s/_build\/onekeydevdesk/_build\/onekeydevdeskspt15g/g" ./ci.sh
          #sudo chmod +x ./ci.sh && sudo ./ci.sh -b 0 -h 0 -t onekeydevdesk

