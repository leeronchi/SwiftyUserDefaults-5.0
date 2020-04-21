# SwiftyUserDefaults-5.0
SwiftyUserDefaults 5.0 修改


4.0 ~ 5.0修改了部分用法
Defaults.yourKey instead of Defaults[.yourKey]

ps：

extension DefaultsKeys {
    var phone_key: DefaultsKey<String> { .init("userCount", defaultValue: "") }
}
  
使用
Defaults.phone_key
