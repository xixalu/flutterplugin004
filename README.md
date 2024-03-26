# flutterplugin004
dependencies:
  yingzi_flutter_image_cache:
    git:
      url: https://github.com/Yingzi-Technology/yingzi_flutter_image_cache.git
      ref: 1.0.0
YZImageCacheView(
    width: 120,
    height: 120,
    placeholderPath: "lib/res/icon_default_photo.png",
    url: "https://img0.baidu.com/it/u=3573430833,889588534&fm=253&fmt=auto&app=138&f=PNG?w=762&h=500",  
)


[width] 图片宽度
[height] 图片高度
[url] 图片地址
[placeholderPath] 支持本地asset图片
[fit] 图片适配方式，只支持BoxFit.contain, BoxFit.cover
[cacheKey] 缓存标识
[isAutoStableCacheKey] 一般不用！是否由系统自动以url排除query后的地址作为缓存标识，如果[cacheKey]值不为空则这个参数失效，如果 [cacheKey] 和 [isAutoStableCacheKey]都没传值默认 [url] 为标识
