# GenAI 기초 2: 멀티모달 콘텐츠 제작
## 1. 브랜드 아이덴티티 및 캠페인 정의

- **브랜드명:** 리브리너 (LeGreener)
    - 프랑스어 정관사 **Le**와 더 푸르른을 뜻하는 영어 **Greener**
- **타겟:** 2030 가치소비를 지향하고 미니멀리즘+웰니스를 추구하는 남녀
- **톤앤매너:** 깨끗함, 차분함, 미니멀리즘, 자연 친화적 시네마틱 무드
- **USP (차별점):** 100% 식물성 유기농 원료 및 생분해 가능한 친환경 패키지 적용
- **광고 목적:** 브랜드 인지도 제고
- **핵심 메시지:** "자연에서 얻고, 자연으로 돌아가다."

## 2. 씬별 상세 스토리보드

### 2.1 씬 01 (Intro) — [이미지]

- **씬 길이(초):**  2.63초
- **목표 메시지:** 자연의 순수함과 깨끗함을 시각적으로 각인
- **화면 구성:**
    - **피사체:** 초록색 잎사귀 끝에 맺힌 이슬
    - **배경:** 아침 햇살이 은은하게 번지는 안개 낀 숲 (몽환적인 분위기)
    - **텍스트:**  capcut에서 상단 여백에 나레이션 자막 배치
- **나레이션:** "모든 아름다움은 자연에서 시작됩니다."
- **사용 도구와 이유:**
    - 이미지: GPT Image2(네이토)
        - 이유: 물방울의 미세한 질감을 극대화된 이미지 확보하기 위해서
    - 오디오 (BGM): Suno AI
        - 이유: 자연의 새소리 효과음과 차분한 분위기 음악을 믹싱 프롬프트로 제어하여 브랜드의 분위기에 맞는 연주곡 만들기 위해서
    - 오디오 (TTS): elevenlabs (목소리: Dan - Calm, Measured and Clear)
        - 이유: 친환경 브랜드의 차분한 분위기를 극대화하기 위해서 그의 분위기에 맞는 Dan의 목소리를 선택
- **입력 프롬프트:** High-resolution professional commercial photography. Extreme close-up shot of a single transparent water droplet on a vibrant green leaf, morning dew, soft cinematic sunlight, misty forest background, hyper-realistic, 8k, shallow depth of field
- **출력 결과 요약:** 물방울이 돋보이는 고화질 세로형 이미지 생성
- **생성 결과 파일명:** scene01_leaf_dew.png

### 2.2 씬 02 (Body) — [영상]

- **씬 길이(초):** 2.84초
- **목표 메시지:** 자연과 인간과 제품의 조화로운 무드를 전달
- **화면 구성:**
    - **피사체:** 리브리너 비건 화장품(미니멀한 유리병)을 두 손으로 감싸 쥔 모델의 손
    - **배경:** 화이트와 우드 톤의 미니멀한 공간
    - **텍스트:** capcut에서 상단과 하단에 나뉘어 나레이션 자막 배치
- **나레이션:** "피부에 닿는 것까지, 가장 순수하게."
- **사용 도구와 사용 목적:**
    - 비디오: 네이토에 있는 OpenAI Sora 2
        - 이유: 물과 제품 패키지의 부드러운 질감, 자연스러운 카메라 무빙 및 대나무 숲 반사 효과 등을 왜곡 없이 생성하기 위해서
    - 오디오 (BGM): Suno AI
        - 이유: 자연의 새소리 효과음과 차분한 분위기 음악을 믹싱 프롬프트로 제어하여 브랜드의 분위기에 맞는 연주곡 만들기 위해서
    - 오디오 (TTS): elevenlabs (목소리: Dan - Calm, Measured and Clear)
        - 이유: 친환경 브랜드의 차분한 분위기를 극대화하기 위해서 그의 분위기에 맞는 Dan의 목소리를 선택
- **입력 프롬프트:** A slow-paced commercial film video. Cinematic medium shot. A person's elegant hands are gently cradling a minimalist, organic matte-glass cosmetic bottle. The background is a serene, sunlit bathroom interior with warm wooden and soft white stone textures. The camera performs an ultra-slow, continuous cinematic push-in movement. Soft focus on the background, natural cinematic lighting, warm and peaceful wellness lifestyle mood. No distorted human features, calm and high-end aesthetic.
- **출력 결과 요약:** 인물의 손 디테일과 유리병의 반사 효과가 고급스럽게 표현된 영상
- **생성 결과 파일명:** scene02_product_motion.mp4

### 2.3 씬 03 (Outro - CTA) — [이미지]

- **씬 길이(초):** 3.7초
- **목표 메시지:** 핵심 슬로건과 브랜드를 명확하게 인지시키며 여운을 남기기
- **화면 구성:**
    - **배경:** 따뜻한 베이지 톤의 자연스러운 리넨 질감 위로 부드러운 나뭇잎 그림자가 드리워진 화면
    - **텍스트:** capcut에서 영상 정중앙에 브랜드명 LeGreener와 슬로건 자막 삽입
- **나레이션:** "자연에서 얻고, 자연으로 돌아가다. LeGreener"
- **사용 도구와 사용 목적:**
    - 이미지: GPT Image2(네이토)
        - 이유: 자막이 돋보여야 하므로 깔끔하고 감성적인 리넨 질감의 사진을 생성
    - 오디오 (BGM): Suno AI
        - 이유: 자연의 새소리 효과음과 차분한 분위기 음악을 믹싱 프롬프트로 제어하여 브랜드의 분위기에 맞는 연주곡 만들기 위해서
    - 오디오 (TTS): elevenlabs (목소리: Dan - Calm, Measured and Clear)
        - 이유: 친환경 브랜드의 차분한 분위기를 극대화하기 위해서 그의 분위기에 맞는 Dan의 목소리를 선택
- **이미지 입력 프롬프트:** Minimalist beige linen fabric texture background, soft organic leaf shadow overlay, clean, simple, warm lifestyle aesthetic, high resolution commercial stock photo
- **출력 결과 요약:** 고해상도 베이지색 리넨 원단 질감 배경에 부드러운 자연스러운 나뭇잎 그림자 오버레이 이미지 생성
- **생성 결과 파일명:** scene03_outro_bg.png

### **2.4 대체 도구 리스트**

- 비디오: Runway Gen-3
- 이미지: Midjourney
- 오디오(bgm): Udio
- 오디오(tts): 타입캐스트

## 3. 프롬프트 개선 로그

- **대상 씬:** 씬 1,2,3 모두 포함한 오디오 bgm
- **수정 전 프롬프트:** nature forest sound, birds chirping
- **문제점:** Suno AI의 특성상 단순 효과음 지시어만 넣으면 음악 비트가 과하게 들어가 새소리가 완전히 묻히는 현상 발생
- **수정 후 변경 사항:** 프롬프트 맨 앞에 현장 녹음 느낌의 Field recording of birds chirping을 배치하고, 악기 소리를 제어하기 위해 very soft acoustic guitar, birds sound focus 등의 구체적인 믹싱 지시어 추가.
- **입력 프롬프트:** Field recording of birds chirping, cinematic ambient background music, very soft acoustic guitar, nature forest sound effects, birds sound focus, prominent nature sounds, slow tempo, peaceful, calm
- **결과 변화:** 음악 선율이 자연스럽게 배경으로 깔리면서 숲속의 싱그러운 새소리가 전면에 강조되어 브랜드의 청량하고 차분한 무드 구현

## 4. 최종 인코딩 및 통합 편집 스펙

- **파일명:** LeGreener_Branding_Video_Final.mp4
- **총 길이:** 9.17초
- **해상도:** 1080x1920 (9:16 세로형)
- **프레임레이트:** 30 fps
- **비디오 코덱:** H.264 / **오디오 코덱:** AAC
- **통합 편집 흐름 (CapCut):**
    1. 생성된 [사진 1] ➔ [영상 2] ➔ [사진 3] 순서대로 배치
    2. [사진 1]에서 [영상 2]와 [사진 3]의 따뜻한 분위기에 맞추기 위해 색감의 온도를 높임
    3. 화면의 여백과 가독성 고려하여 모든 씬에 제주명조체로 내레이션 자막을 삽입 후 모든 자막에 페이드 아웃 애니메이션을 적용, 마지막 자막(브랜드명)에는 페이드 인 애니메이션 적용
    4. Suno AI로 추출한 새소리 기반 MP3 BGM과 TTS 나레이션 추가 최종 비디오 파일로 렌더링

## **5. 보너스 과제 -** 동일 스토리보드, 다른 도구로 재제작

- 이미지 또는 비디오 생성 파트를 다른 도구로 바꿔 동일 씬 1~2개를 재제작하기 (위와 동일한 프롬프트)

### 5.1 모델 설명

- 이미지 생성 (씬 01,03 재제작): 레오나르도 AI (무료)
    - 선정 사유: 실사 사진 메커니즘에 특화된 전용 엔진을 제공하고 GPT Image2보다 물방울의 투명한 표면 장력과 햇살이 잎사귀에 반사되는 디테일을 더 현실감 있게 표현할 수 있어 브랜드의 분위기를 강화하기 위해 선택
- 비디오 생성 (씬 02 재제작): 루마 드림머신 (무료)
    - 선정 사유: OpenAI Sora 2처럼 고화질 Text-to-Video 렌더링 능력을 갖춤. 친환경 브랜드가 요구하는 카메라 무빙을 왜곡 없이 무료 플랜 내에서 구현할 수 있기 때문

### 5.2 최종 비교 평가

- 동일한 스토리보드와 프롬프트 바탕으로 재제학한 결과, 카메라 연출 제어력 측면에서 레오나르도 ai랑 루마 드림머신이 GPT Image2랑 Sora 2보다 우수한 결과물을 보여줌
- Sora 2의 경우 화장품을 든 모습을 단순히 정적인 구도로 유지한 반면, 루마 드림머신은 제품을 향해 천천히 확대해 들어가는 시네마틱 무빙이라는 명령어를 정확하게 인지하고 시각화함

이 비교 실험을 통해 비디오 생성 AI를 선택할 때는 단순히 화질뿐만이 아니라 기획자가 의도한 카메라 무빙과 연출 지시를 얼마나 정확하게 물리적으로 구현해 내는지를 최종 영상의 완성도를 결정짓는 요인이라는 것을 알 수 있었음
