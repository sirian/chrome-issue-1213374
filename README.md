# chrome-issue-1213374

1. Sometimes devtools displays cross-origin WindowProxy as `global` but sometimes as `Window`
2. Why `console.log(crossOriginWindow)` throws, but `console.log([crossOriginWindow])` - not? Firefox, Safari doesn't throw in both cases

![image](https://user-images.githubusercontent.com/897643/120670956-97c14c00-c499-11eb-8b21-61c493b0b327.png)


Firefox output - no errors, all cross origin windows displayed as "Restricted" (as expected)

![image](https://user-images.githubusercontent.com/897643/120672930-68abda00-c49b-11eb-8bdb-efd0d77f29d3.png)
