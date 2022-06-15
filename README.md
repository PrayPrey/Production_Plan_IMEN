# Production_Plan_IMEN
생산계획 프로젝트(MPS, MRP 전개)을 위해 작성한 코드입니다.
Chasing / L4L 전략을 따르는 것으로 가정하였습니다.


- Class 3개로 이루어져 있으며, 각 클래스는 다음을 의미합니다.
- 모든 Class에서 저장 과정은 엑셀로 입력, 저장하도록 설정해두었습니다.


1) Production Class : Forecast, Order을 받아서 MPS, MRP 전개 (Excel). 이때 MRP의 PAB는 이후 PAB가 0이 나오도록 최적의 값으로 두었습니다.
2) Final Class : 여러 Product로부터 전개된 MPS, MRP를 하나로 합쳐주는 Class (Excel)
3) Merged Class : 1주차 2주차, n주차의 Actual value이 나올 시 MRP, MPS가 어떻게 변화하고 전개되는지 나타내어주는 Class 입니다.

- 추가적인 사항은 ipynb 파일 내의 주석으로 작성하였습니다. (BOM 작성방법 등등..)
