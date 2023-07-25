# performance
웹 성능 최적화

### Audits(Listhouse)
- 성능 검사 툴


### 이미지 최적화  
* cdn 사용? -> contents Delivery Netwrok 물리적 거리의 한계를 극복하기 위해 소비자와 가까운 곳에 컨텐츠 서버를 두는 기술  
  * image processing CDN:  htttp:/cdn.image.com?src?[img src]&width=200&heigth=100
```
// image CDN 역활
function getParametersForUnsplash({width, height, quality, format}) {
  return `?w=${width}&h=${height}&q=${quality}&fm=${format}&fit=crop`
}
```
### Minify JavaScript 최적화 
- 주석, 공백 제거  

