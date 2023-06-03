# 🔥kaggleCompetition🔥

## 📁 Directory hierarchy

트리

### Convention

- 각 대회별로 폴더가 구성되어 있습니다. 대회 폴더 내부에는 Main Folder와 멤버 이름 Folder가 있습니다.
- Main Folder에는 최종 제출할 모델과 대회의 데이터셋이 저장되어 있습니다.
- Main Folder 내부의 dataset 폴더에는 Data들이 들어가 있으며, GitIgnore로 데이터는 Git에 올리지 않습니다.
- Main Folder 내부의 model 폴더에는 competition에 제출할 모델이 들어갑니다.
- 각 멤버 이름으로 된 폴더에는 본인이 실험적으로 진행해 볼 파일들이 들어갑니다.

## ⭐️ Git Convention

### Issue Title

- [PREFIX] 구현할 내용
- EX : [FEAT] CNN 모델 구현

### Commit Message

- [#이슈번호] PREFIX: 구현한 내용
- EX : [#3] FEAT: CNN Model 객체 완성
- Commit 단위는 최대한 작게 가져가기

### Pull Request Title

- [#이슈번호] PREFIX: 구현한 내용
- EX : [#5] FEAT: CNN 모델 구현

### PREFIX

<img src="https://drive.google.com/uc?id=1klDIcVKRYaFNGjtLE4-0QKlZPUVgMBAJ" width=600>

### Git Flow

- Main Branch와 작업 Branch로 나뉩니다.
- 작업 Branch에서 작업이 완료되고 Main Branch로 Merge 하고자 할 때 PR를 날립니다.
- PR 내용을 검토하고 Approve가 되면 Merge 합니다.
- 만약 Merge를 하는 과정에서 Collision이 발생한다면 카톡으로 연락을 보냅니다.
- Branch 이름: Prefix/이슈번호
