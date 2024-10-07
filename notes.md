# PYTHON <br/>
The Purpose of the if __name__ == '__main__': (KOREAN) <br/>
-> [Link1] 파이썬은 import 파일의 모든 요소가 실행되기 때문, 방지 차원에서 사용하는 라인 <br/>
The Purpose of the super(클래스,self).__init__() <br/>
-> [Link4] 자식 클래스(Student)가 상속받는 부모 클래스(Human)를 자식 클래스(Student)에 불러오겠다는 의미 <br/>
If Float error occurs by the deprecated Numpy version, use the following codes <br/>
```
np.float = float
np.int = int   #module 'numpy' has no attribute 'int'
np.object = object    #module 'numpy' has no attribute 'object'
np.bool = bool    #module 'numpy' has no attribute 'bool'
```

# PYTORCH <br/>
Difference of Map-style dataloader and Iterable dataloader (KOREAN): <br/>
-> [Link2] Parallel 사용시 데이터가 중복될 수 있으니 유의할 것<br/>

__init__() 선언시, 다른 레이어는 별도로 호출해야 한다.[Link3] <br/>

# DEEP LEARNING<br/>
-> [Link5] Nemo Speaker Model 훈련 예정<br/>
# GIT<br/>
Three stages to commit a file<br/>
add     : adding the file to the staging area<br/>
commit  : commit the file to the git (make sure to follow git convention)<br/>
push    : upload the commit to the github<br/>

# REGEX<br/>
문장부호 + 한국어 를 regex로 일괄수정하는 방법<br/>
txt = re.sub("([?!.,\]])([가-힣])", r"\1 \2", txt) #괄호는 \1를 대변함 <br/>
[Link1]: https://velog.io/@mjk3136/if-name-main%EC%9D%80-%EC%99%9C-%ED%95%84%EC%9A%94%ED%95%9C%EC%A7%80%EC%97%90-%EB%8C%80%ED%95%B4-%EC%95%8C%EC%95%84%EB%B3%B4%EC%9E%90
[Link2]: https://inmoonlight.github.io/2021/02/21/PyTorch-IterableDataset/
[Link3]: https://discuss.pytorch.org/t/which-one-is-correct-to-initialize-separate-layer/55640
[Link4]: https://supermemi.tistory.com/entry/Python-3-super%ED%81%B4%EB%9E%98%EC%8A%A4-selfinit-%EC%97%90-%EB%8C%80%ED%95%B4-%EC%A0%9C%EB%8C%80%EB%A1%9C-%EC%95%8C%EC%95%84%EB%B3%B4%EC%9E%90
[Link5]: https://github.com/NVIDIA/NeMo/blob/main/tutorials/speaker_tasks/Speaker_Identification_Verification.ipynb
