# cocoapodsTest
![](https://raw.githubusercontent.com/dsxNiubility/SXWaveAnimate/master/screenshots/waveAnimate0.gif)
``` Objective-C
- (BOOL)application:(UIApplication *)application openURL:(NSURL *)url sourceApplication:(NSString *)sourceApplication annotation:(id)annotation
{
    [SPay handleOpenURL:url withCompletion:^(NSString *result, SPayError *error) {
        // 支付成功
        if ([result isEqualToString:@"success"]) {
 
        }else{
            // 支付失败
        }
    }];
    return YES;
}
```
#一级标题  
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题 
