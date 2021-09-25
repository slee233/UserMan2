# UserMan2
Sample project for DBP class in 2021
based on MVC architecture 

### update branch
- branched from master 
- integrates UpdateUserFormController & UpdateUserController

### master로부터 변경된 클래스 및 JSP

- controller.RequestMapping: "/user/update"에 대한 request mapping 수정
- controller.user.UpdateUserFormController: 기능을 UpdateUserController에 병합하고 삭제됨
- controller.user.UpdateUserController: UpdateUserFormController 기능 포함
- /user/view.jsp: 수정 링크에 대한 request URI를 "/user/update" 로 수정
     
  
