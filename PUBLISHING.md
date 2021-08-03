```
git add .
git commit -m "utils: changes for v0.2.1"
git tag v0.2.1
git push origin v0.2.1
git push
GOPROXY=proxy.golang.org go list -m github.com/andrewlunde/thetaoffchaingo_utils@v0.2.1

go get github.com/andrewlunde/thetaoffchaingo_utils@v0.2.1
  
// in go.mod of application using this module
require github.com/thetatoken/theta/utils v0.0.0
replace	github.com/thetatoken/theta/utils v0.0.0 => github.com/andrewlunde/thetaoffchaingo_utils v0.2.1

```

