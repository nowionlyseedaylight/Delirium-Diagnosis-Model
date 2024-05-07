# Delirium-Diagnosis-Model

## ✅ 와상환자의 잠재위험 예방을 위한 자세분류 및 알림 시스템
Deep learning / Monitoring / Object Detection / Pose Classification / Middleware

와상환자 잠재위험 간의 연관성에 주목하여 융합적인 진단을 목표로 하는 위험 예측 시스템을 구현했습니다. 와상환자 케어의 어려움으로 제기되는 낙상과 욕창을 영상인식을 통해 판단합니다. skeleton을 추출하는 딥러닝 모델을 활용해 자세를 분류하고 그래프를 통해 변화 양상을 실시간으로 확인하며, 침대이탈 상황인 낙상과 부동자세인 욕창을 예측할 수 있습니다.

낙상과 욕창은 판별 대상임과 동시에 각각 과활동형 섬망, 저활동형 섬망을 진단하는 지표로도 활용되며 시간 변화율로 간접 진단합니다. 초기 진단이 어려운 섬망의 잠재대상을 자동화 시스템을 통해 선별하여 기존의 사정도구로 빠르게 연결한다는 점에서 의의를 갖습니다. 전체 시스템은 미들웨어를 적극 활용하여 긴밀하게 짜여있으며 특정 기준을 만족하는 위험이 발생한 경우 돌봄인력에게 알림을 보내는 서비스를 함께 제공합니다.

본 프로젝트의 주제로 작성한 [논문](https://kiss.kstudy.com/Detail/Ar?key=3988623)도 확인해보실 수 있습니다.

## Project Introduction: Multifaceted Risk Prediction System for Elderly Patients

We have developed a comprehensive risk prediction system that aims to amalgamate diagnostics by focusing on the interrelation between falls and pressure ulcers in elderly patients. Addressing the challenges in elderly patient care, we employ image recognition to assess the occurrences of falls and pressure ulcers. We utilize a deep learning model for skeleton extraction to classify postures and analyze changes in real-time through graphical representations. This allows us to predict situations of falls, known as bed exits, and pressure ulcers due to immobility.

Both falls and pressure ulcers serve as indicators for discerning their respective targets while indirectly diagnosing hyperactivity and hypoactivity syndromes, all based on the rate of temporal changes. The system holds significance in swiftly identifying potential candidates for the elusive syndrome through automation, which can be challenging with conventional assessment tools. Leveraging middleware extensively, the entire system is meticulously orchestrated, and it also provides a notification service to caregivers when risks meeting specific criteria arise.

You can also view the [paper](https://kiss.kstudy.com/Detail/Ar?key=3988623) written on the project's topic.
