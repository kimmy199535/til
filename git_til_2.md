- repository를 이용하는 법을 배웠다.
    - Git으로 관리되는 프로젝트 를 Git 에서는 repository(repo)라 부른다고 한다.
- git에 자료를 커밋하고, 커밋한 내용을 github에 있는 원격 저장소에 추가하는 것 - 협업 시작!

---

### 2. Local/Remote Repo가 뭘까

#### 로컬 Repo (Local Repository)
- 내 컴퓨터에 저장되어 있는 개인용(local) 저장소다.
- 로컬에 저장하는 내역이 타인(협업하는 사람)에게 바로 공유가 되는 것은 아니다.
    - commit하면 바로 공유!  << 이게 아님
    - 원격 Repo에 공유해야 협업하는 사람들과 내가 작업한 작업 내역이 공유된다.
   
<br>

#### 원격 Repo (Remote Repository)
- Github 같이 내 로컬 환경이 아닌 다른 곳에 접속되어 있는 저장소를 원격 Repo라고 한다.
    - 로컬 Repo만이 내가 어떤 원격 Repo와 연결되어 있는지 알고 있다.
    - 원격 Repo는 내가 어떤 로컬 Repo와 연결되어 있는지 확인할 수 없다.
    - 로컬 Repo가 원격 Repo에 연결하는 것을 <span style ="color:pink">""Tracking"</span>이라고 한다.
    - 로컬은 있고 원격은 없을 때!
    <br>
    
- 보통 github을 많이 사용하고, 로컬 Repo에 저장된 내역을 원격 Repo로 옮기는 작업은 협업에 있어 필수적이다.
    - 이때 옮기는 작업을 <span style ="color:pink">"push"</span>라고 한다.
	<br>
- 원격 Repo에 있는 내용은 다른 사람이 작업한 내용이 push 되어있기 때문에, 코드를 로컬로 가져와야 한다.
    - 이때 다른 사람이 작업한 내용은 내 로컬에 반영 시키는 작업을 <span style ="color:pink">"pull"</span>이라고 한다.
    <br>
- 협업을 하기 위해선 원격 Repo를 초반에 내 로컬에 가져오는 초기 작업이 필요하다.
    - 이때 복사하는 작업을 <span style ="color:pink">"clone"</span>이라고 한다.
    - 원격은 있고 로컬이 없을 때!

<br>

---

### 3. 간단한 git 플로우 정리:
![](https://velog.velcdn.com/images/hailey199535/post/bc198597-e5a8-49a7-86db-9c5f7e96a8ef/image.png)

---