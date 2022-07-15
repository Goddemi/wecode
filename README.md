<h1>git 명령어 활용</h1>

<h3>git add</h3>
<p>git add는 작업 디렉토리(working directory) 상의 변경 내용을 스테이징 영역(staging area)에 추가하기 위해서 사용하는 Git 명령어입니다.</p>
<p>git add 명령어를 사용할 때, 항상 함께 사용하게 되는 명령어가 git status 입니다. git status 명령어는 작업 디렉토리(working directory)와 스테이징 영역(staging area)의 상태를 확인하기 위해서 사용합니다.</p>

<h3>staging area</h3>
<p>스테이징 영역은 작업 디렉토리와 Git 저장소의 변경 이력 사이에 징검다리 역할을 하는데요. 작업 디렉토리는 아직 커밋할 준비가 안된 변경 내용을 자유롭게 수정할 수 있는 공간인 반면에, 스테이징 영역은 커밋할 준비가 된 변경 내용이 Git 저장소에 기록되기 전에 대기하는 장소라고 생각할 수 있습니다. git add 명령어를 사용하면 현재 작업 디렉토리에 있는 모든 또는 일부 변경 내용을 스테이징 영역으로 이동시킬 수 있습니다. </p>

<h3>git remote</h3>
<p>리모트 추가 git remote add <pre><name> <url></pre></p>
<p>리모트 제거 git remote remove <pre> <name></pre></p>
