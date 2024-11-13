- 开启任何来源  
 `sudo spctl --master-disable`

- 签名修复  
 `sudo xattr -rd com.apple.quarantine ` (空格)

- 强制修复  
 `sudo codesign --sign - --force --deep`