---
title:  "[VMWARE] 가상머신 여러 개 실행 시 page fault 블루스크린 발생"
excerpt: "VMWARE 가상머신 in Window 10"

categories:
  - Vmware
tags:
  - [VMmware]

toc: true
toc_sticky: true
 
date: 2022-02-18
last_modified_at: 2022-02-18
---

## Intro  

Vmware 가상 머신이 여러개 존재 할 때, 여러 가상머신을 동시에  
켜야 할 때가 존재한다. 이 때 메모리 부족 문제가 아님에도  
두번 째 가상머신이 Power On될 때 "PAGE FAULT IN NONPAGE AREA"  
메세지와 함께 블루 스크린이 뜬다면 하기와 같은 설정을 해보자  


## VMWARE 설정  
![1_setting](/assets/image/1_vmware/1_page_fault/1_setting.png)  

위 사진처럼 해당 가상머신에 오른쪽 마우스를 클릭하여 Settings...  
를 클릭한다. 
  
![2_hardware](/assets/image/1_vmware/1_page_fault/2_hardware.png)  

Hardware탭을 누르면 보이는 Device들 중 필요없는 Device를 선택한다  

![3_Remove](/assets/image/1_vmware/1_page_fault/3_Remove.png)  

Device를 선택 후 Remove 를 클릭한다.
