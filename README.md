# chrome-issue-1213374

1. Sometimes devtools displays cross-origin WindowProxy as `global` but sometimes as `Window`
2. Why `console.log(crossOriginWindow)` throws, but `console.log([crossOriginWindow])` - not? Firefox, Safari doesn't throw in both cases

![image](https://user-images.githubusercontent.com/897643/120670956-97c14c00-c499-11eb-8b21-61c493b0b327.png)
