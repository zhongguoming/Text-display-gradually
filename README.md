# Text-display-gradually
文字渐渐显示，文字渐变，就是文字从左往右依次显示，效果就像是一行一行从上往下显示。
基础使用Demo：

    let blingBlingLabel = FNBlingBlingLabel.init(frame: CGRectMake(0, 0, 300, 200))
    blingBlingLabel.needAnimation = true
    blingBlingLabel.numberOfLines = 0
    blingBlingLabel.textColor = UIColor.whiteColor()
    blingBlingLabel.appearDuration = 1.5
    blingBlingLabel.disappearDuration = 1.5
    self.view.addSubview(blingBlingLabel)
    blingBlingLabel.text = "FNBlingBlingLabel-TestString
    
借用大神"Fnoz/FNBlingBlingLabel，只是简单修改下适合自己的需求   
 
![image](https://raw.githubusercontent.com/zhongguoming/Text-display-gradually/441db0297688eae068c6744c9a265e7626b66571/TextDisplay/TextDisplay.gif)
