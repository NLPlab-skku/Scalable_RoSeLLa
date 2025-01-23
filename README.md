# Scalable_RoSeLLa
언어 모델의 사이즈를 축소 및 확장하는 기법을 적용한 sLM 모델을 위한 페이지 입니다.
현재 사용되는 언어모델 Scalable 방식을 적용하여 진입장벽이 낮은 3B 모델을 만드는 것이 목표입니다.

Scalable을 위한 모델을 위해 기반 모델은 [Qwen2.5](https://huggingface.co/collections/Qwen/qwen25-66e81a666513e518adb90d9e) 시리즈를 사용하였습니다. 

## RoSeLLa_Solar
[Qwen2.5-1.5B](https://huggingface.co/Qwen/Qwen2.5-1.5B) 모델을 [Solar](https://arxiv.org/abs/2312.15166) 방식을 통해 업스케일링한 모델입니다.
다음과 같은 파라미터들이 변경되었습니다.

Hugginface : 
