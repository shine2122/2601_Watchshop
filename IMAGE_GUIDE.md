# 이미지 추가 가이드

이 웹사이트는 실제 시계 이미지를 표시하도록 설정되어 있습니다. 나노-바나나(또는 다른 AI 이미지 생성 도구)를 사용하여 이미지를 생성하고 추가하세요.

## 필요한 이미지 목록

### 1. 히어로 섹션 메인 시계
- **파일 경로**: `images/hero/zenith-main.jpg`
- **권장 크기**: 1000x1000px
- **프롬프트 예시**:
  ```
  luxury gold and black skeleton chronograph watch, rose gold case,
  black leather strap, premium horological masterpiece,
  studio product photography, white background, high-end luxury timepiece,
  detailed mechanical movement visible through transparent dial
  ```

### 2. 제품 컬렉션 시계들 (4개)

#### The Chronos
- **파일 경로**: `images/watches/chronos.jpg`
- **권장 크기**: 600x800px
- **프롬프트**:
  ```
  luxury watch with brown leather strap, minimalist white dial,
  rose gold case, classic elegant design, product photography, white background
  ```

#### The Ethereal
- **파일 경로**: `images/watches/ethereal.jpg`
- **권장 크기**: 600x800px
- **프롬프트**:
  ```
  luxury all-black watch, minimalist midnight design,
  black metal band, sleek modern aesthetic, matte black dial,
  product photography, white background
  ```

#### Aurora Rose
- **파일 경로**: `images/watches/aurora-rose.jpg`
- **권장 크기**: 600x800px
- **프롬프트**:
  ```
  luxury rose gold watch, elegant pink dial, rose gold bracelet,
  feminine sophisticated design, admiral collection,
  product photography, white background
  ```

#### Manoli
- **파일 경로**: `images/watches/manoli.jpg`
- **권장 크기**: 600x800px
- **프롬프트**:
  ```
  classic luxury watch, silver stainless steel case,
  green sunburst dial, silver metal bracelet, traditional elegant design,
  product photography, white background
  ```

### 3. Featured Story 배경 이미지
- **파일 경로**: `images/story/featured-bg.jpg`
- **권장 크기**: 1920x600px
- **프롬프트**:
  ```
  close-up of person wearing luxury watch on wrist in golden sunset light,
  warm atmospheric lighting, bokeh background, cinematic photography,
  inspirational moment, time and light concept
  ```

### 4. Heritage 섹션 이미지
- **파일 경로**: `images/heritage-bg.jpg`
- **권장 크기**: 800x600px
- **프롬프트**:
  ```
  vintage watchmaking tools and components, close-up macro photography,
  warm ambient lighting, artisan craftsmanship, traditional horology,
  gears and springs, nostalgic vintage aesthetic
  ```

## 이미지 생성 방법 (나노-바나나 사용)

1. 나노-바나나 웹사이트 또는 앱을 엽니다
2. 위의 프롬프트를 복사하여 붙여넣습니다
3. 이미지 크기를 권장 크기로 설정합니다
4. 고품질(HD) 옵션을 선택합니다
5. 생성된 이미지를 다운로드합니다
6. 해당 파일 경로에 저장합니다

## 폴더 구조

```
/home/user/2601_Watchshop/
├── images/
│   ├── hero/
│   │   └── zenith-main.jpg          (메인 히어로 시계)
│   ├── watches/
│   │   ├── chronos.jpg              (The Chronos 시계)
│   │   ├── ethereal.jpg             (The Ethereal 시계)
│   │   ├── aurora-rose.jpg          (Aurora Rose 시계)
│   │   └── manoli.jpg               (Manoli 시계)
│   ├── story/
│   │   └── featured-bg.jpg          (스토리 배경)
│   └── heritage-bg.jpg              (Heritage 배경)
├── index.html
├── styles.css
└── IMAGE_GUIDE.md
```

## 이미지 최적화 팁

- **파일 형식**: JPG 또는 PNG (JPG 권장, 파일 크기가 작음)
- **파일 크기**: 각 이미지 500KB 이하로 최적화
- **해상도**: 72-150 DPI (웹용)
- **배경**: 제품 사진은 깨끗한 흰색 배경
- **조명**: 고급스러운 스튜디오 조명 느낌

## 임시 이미지로 테스트하기

이미지가 아직 준비되지 않았다면, 임시로 무료 이미지를 사용할 수 있습니다:
- [Unsplash](https://unsplash.com/s/photos/luxury-watch)
- [Pexels](https://www.pexels.com/search/luxury%20watch/)

검색어: "luxury watch", "chronograph watch", "rose gold watch" 등

## 이미지 추가 후

이미지를 모두 추가한 후:
1. 브라우저에서 `index.html`을 열어 확인
2. 모든 이미지가 제대로 표시되는지 확인
3. Git에 커밋하고 푸시
4. Netlify에 재배포

```bash
git add images/
git commit -m "Add watch product images"
git push
```
