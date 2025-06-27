# Price

## Price

#### TEXT <a href="#text" id="text"></a>

> **Komodo** NLP(Natural Language Processing) 기술을 활용한 채팅 서비스는 사용자의 질문이나 요청을 실시간으로 이해하고 대응하는 대화형 인터페이스를 제공합니다. 이 서비스는 고객 지원, 교육, 엔터테인먼트 등 다양한 분야에서 더 정확하고 유용한 대화 경험을 제공합니다.

ModelInference InputInference Output

KOMODO-SMALL

0.0007₩ / 토큰 (700₩ / 1M 토큰)

0.0007₩ / 토큰 (700₩ / 1M 토큰)

KOMODO-LARGE

0.002₩ / 토큰 (2,000₩ / 1M 토큰)

0.002₩ / 토큰 (2,000₩ / 1M 토큰)

#### AUDIO <a href="#audio" id="audio"></a>

> **STT**
>
> STT(Speech to Text) 기술은 사용자의 음성 데이터를 텍스트로 변환하는 시스템입니다. 이 기술은 음성 명령 입력, 음성 기반 챗봇, 음성 메모 등 여러 응용 프로그램에 활용되어 다양한 서비스와 기능에 적용할 수 있습니다.

ModelAudio Input

STT

0.3₩ / 초 (18₩ / 분)

> **TTS**
>
> TTS(Text to Speech) 기술은 작성된 텍스트를 합성 음성으로 변환하여 청취할 수 있게 해주는 시스템입니다. 이 기술은 가상 어시스턴트, 오디오북, 음성 안내 시스템 등에 사용되어 사용자들이 텍스트 정보를 듣는 방식으로 접근할 수 있게 해줍니다.

ModelText Input

TTS

0.06₩ / 글자

#### IMAGE <a href="#image" id="image"></a>

> **OCR**
>
> OCR(Optical Character Recognition) 기본 모델은 이미지에서 텍스트를 인식하고 디지털 형식으로 변환하는 기술입니다. 이 모델은 문서 스캔, 사진 속 글자 추출, 자동화된 데이터 입력 등에 사용되며, 문자를 정확하게 인식하여 편집 가능한 텍스트로 변환합니다. OCR 기술은 효율적인 문서 처리와 데이터 관리를 가능하게 하며, 디지털화된 환경에서의 정보 접근성을 높여줍니다.

ModelImage Input

OCR

25₩ / 건

#### MULITMODAL <a href="#mulitmodal" id="mulitmodal"></a>

> **MARS**
>
> MARS는 강력한 LLM이 결합한 Vision Language Model 입니다. VQA(Vision Question Answering)에 대한 강력한 성능으로 이미지에 대한 고차원적인 추론이 가능합니다. 시각적 데이터의 해석 및 분석이 필요한 분야에 혁신적인 솔루션을 제공합니다.

ModelInference InputImage InputInference Output

MARS

0.0007₩ / 토큰 (700₩ / 1M 토큰)

0.0672₩ / 슬라이스

0.0007₩ / 토큰 (700₩ / 1M 토큰)

**이미지 토큰 변환**

* **슬라이스 수 결정** 이미지가 몇 개의 448x448px 사각형으로 나뉘는지 계산합니다. \* 최대 슬라이스 수는 9장(1344x1344px)입니다. \* 최대 해상도 기준을 초과하는 경우 1344x1344px로 이미지 크기를 조정합니다.
