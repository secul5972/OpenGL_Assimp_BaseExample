프로젝트 속성 -> 디버그 -> 환경에 PATH=$(SolutionDir)$(SolutionName)\lib;%PATH% 추가

//아래는 적용 되어있음
시작 '\'는 지우고 넣기

c/c++ -> 일반 -> 추가 포함 디렉터리 \$ (SolutionDir)$(SolutionName)\include


링커 -> 일반 -> 추가 라이브러리 디렉터리 \$ (SolutionDir)$(SolutionName)\lib


링커 -> 입력 -> 추가 종속성 assimp-vc143-mtd.lib;glfw3.lib;opengl32.lib;
