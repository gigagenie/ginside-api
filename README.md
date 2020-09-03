# G-INSIDE API



## GiGA Genie Inside 란?

**GiGA Genie Inside (이하, G-INSIDE)**는 3rd party 개발자가 자신들의 제품 (단말 장치, 서비스, 앱 등)에 **KT**의 AI Platform인 `기가지니`를 올려서 음성인식과 자연어로 제어하고 `기가지니`가 제공하는 서비스 (생활비서, 뮤직, 라디오 등)를 사용할 수 있도록 해줍니다. **G-INSIDE**는 `기가지니`가 탑재된 제품을 개발자들이 쉽게 만들 수 있도록 개발 도구와 문서, 샘플 소스 등 개발에 필요한 리소스를 제공합니다.



## G-INSIDE API란?

G-INSIDE API는 기가지니 Cloud AI Platform(G-INSIDE 서버)과의 연동 개발을 위해 G-INSIDE 서버에서 제공하는 API로, HTTP/2 기반의 `gRPC` 와 HTTP/1.1 기반 `WebSocket` 프로토콜을 통해 제공됩니다. 

> G-INSIDE에서는 다양한 개발 환경 및 개발 편의성을 위해, Linux, Android(AOSP), Windiws, Web 등 단말 플랫폼에 맞는 클라이언트 SDK(GiGA Genie Inside SDK)를 제공합니다. SDK에 대한 자세한 내용은 [GiGA Genie Inside SDK](https://github.com/gigagenie/ginside-sdk) 를 통해 확인하세요.
>



- [G-INSIDE API 연동 규격서 확인하기](https://github.com/gigagenie/ginside-api/wiki)
- G-INSIDE API 샘플 클라이언트 
  - using gRPC protocol : [sample-client-node](https://github.com/gigagenie/sample-client-node), [sample-client-python](https://github.com/gigagenie/sample-client-python)    
  - using WebSocket protocol : [sample-client-web](https://github.com/gigagenie/sample-client-web)  





