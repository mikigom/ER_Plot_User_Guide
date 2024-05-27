마지막 수정일: 2023/12/06

# 사용자 인터페이스

## 요소

### 선택 바 (상단 바)

1. **비교 드롭다운 (`comparison-dropdown`)**:

<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/684f8224-1860-40eb-afe4-9d504e63f81b" width="200px">
</p>

    - 사용자가 산점도 차트에서 보고 싶은 데이터 비교 유형을 선택할 수 있습니다.
    - 옵션에는 픽률 대 승률, 픽률 대 RP 획득량, Top 3 내에서의 Top 3 비율 대 승률, 평균 팀 킬 수 대 Top 3 비율, RP 획득량 대 승률 등의 비교가 포함됩니다.

2. **버전 드롭다운 (`version-dropdown`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/ae83a0b5-ce1d-4e65-96a0-7f08b9d7cacc" width="200px">
</p>

    - 사용자는 게임 패치 버전을 기반으로 데이터를 필터링할 수 있습니다.
    - 옵션은 이전 버전, 현재 버전, 현재 버전의 마지막 3일, 그리고 현재 버전의 마지막 7일 등이 있습니다.

3. **티어 드롭다운 (`tier-dropdown`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/c0b7f398-842d-4779-84c8-a6f608ec5f0b" width="200px">
</p>

    - 플레이어 티어 순위에 따라 데이터를 필터링합니다.
    - 옵션에는 상위 1000위 내, 다이아몬드+, 플래티넘+ 등이 포함됩니다.

4. **역할 드롭다운 (`role-dropdown`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/79a50e60-b8fd-49cb-b148-1a976f52d9b6" width="200px">
</p>

    - 근접 딜러, 스킬 원거리 딜러, 공격형 원거리 딜러, 탱커, 암살자, 서포터, 사용자 정의 등의 역할에 따라 캐릭터를 필터링합니다.

5. **사용자 정의 그룹 편집 버튼 (`edit-user-defined-roles-button`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/932082cc-60a9-4601-8176-62153edaa9ea" width="150px">
</p>

    - 사용자가 캐릭터의 사용자 정의 그룹을 정의할 수 있는 모달을 엽니다.
    - 모달에서 캐릭터를 클릭하면 해당 캐릭터를 사용자 정의 그룹에 추가하거나 제거합니다.

### 슬라이더 (상단 바 아래)

6. **픽률 슬라이더 (`pick-rate-slider`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/b44313f8-b7b9-4adb-94ad-deb903cc644d" width="800px">
</p>

    - 사용자가 산점도 차트에서 데이터를 필터링하기 위해 픽률 범위를 선택할 수 있습니다.
    - 현재 선택된 픽률 범위를 슬라이더 위에 표시합니다.

### 모달 대화상자

7. **사용자 그룹 정의 모달 (`modal-edit-user-defined-roles`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/0cfd02c4-be41-4e0f-a1c7-ef0411669fce" width="350px">
</p>

    - 열리면 사용자는 자신만의 역할 그룹에 포함시킬 캐릭터를 선택하거나 선택 취소할 수 있습니다.
    - 변경 사항을 반영하기 위해서 `확인`을 눌러야 하며, `초기화`를 누르면 모든 선택이 해제됩니다.

### 그래프 영역

8. **산점도 (`scatter-plot`)**:
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/a62d2c1e-967c-4d40-aff6-1ef07769c3c2" width="450px">
</p>

    - 드롭다운에서 선택된 데이터를 표시하는 주요 상호작용 그래프입니다.
    - 사용자는 자세히 보기 위해 그래프 내에서 패닝과 줌을 할 수 있습니다.

9. **범례 (`legend`)**
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/7d25145b-a9a5-4e6d-8d6b-cdbb60162094" width="200px">
</p>

     - 전체 실험체 그룹과 선택한 실험체 그룹을 색상 별로 표시함을 나타냅니다.
     - 실험체 그룹을 범례에서 선택하여 산점도에 데이터를 포함하거나 제외할 수 있습니다.

10. **모드 바 (`ModeBar`)**
<p align="left">
<img src="https://github.com/mikigom/ER_plot/assets/15151242/7a0c8dba-921f-416a-8ce4-ade3ecce52c3" width="200px">
</p>

    - 산점도에 대한 마우스 동작의 모드를 바꿀 수 있습니다.
    - 현재 보고 있는 산점도를 사진으로 저장하는 기능, Zoom / Pan 전환 기능, 자동 스케일 기능 등이 포함됩니다.

11. **마지막 업데이트 시간 (`last-update-time`)**: 데이터가 마지막으로 업데이트된 시간을 표시합니다.

12. **메뉴얼 페이지 링크 (`Manual Page`)**: 프로젝트 페이지로의 외부 링크로, 현재 보고 있는 이 메뉴얼로 다이렉션 됩니다.

