Shadowrocket

使用说明

Advertising.list，请使用RULE-SET。
Advertising_Resolve.list，请使用RULE-SET。
Advertising_Domain.list，请使用DOMAIN-SET。
URL-REGEX类型的规则，在HTTPS协议中，需要配合MITM使用。规则生成器已尝试推导MITM的配置Advertising_MITM.sgmodule，仅供参考。
文件区别

Advertising_Resolve.list与Advertising.list的区别仅在于后者IP-CIDR(6)类型带no-resolve。
配置建议

Advertising.list、Advertising_Domain.list 共同使用。
Advertising_Resolve.list、Advertising_Domain.list 共同使用。
