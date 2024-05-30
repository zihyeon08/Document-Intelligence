# Vision_Odessy_Guide

## 1. Azure 서비스 구독하기
Azure 서비스를 이용하려면 Azure에 먼저 가입을 해야 합니다.  
<br>  
성인의 경우, 신용카드를 등록해야 Azure 서비스를 사용할 수 있지만  
학생의 경우, 신용카드를 등록하지 않고 Azure 서비스를 사용할 수 있습니다.  
<br>  
### ➤ [학생 : Azure 가입하기](https://github.com/pmj-chosim/howtomake_azureforstudents)  
### ➤ [성인 : Azure 가입하기](https://azure.microsoft.com/ko-kr/get-started/azure-portal)   
<br>  

## 2. IDE에서 개발 환경 셋팅하기  
IDE(Visioual Studio Code)에서 Azure AI 문서 인텔리전스 실습을 위한 환경을 셋팅하겠습니다.  
<br>  
1. Visual Studio Code 열기  <br>  
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/fbcc2166-53c0-47ef-a4fe-1b1837d37971)

2. 확장(Extension) 클릭하기 > .NET 확장 설치하기 <br>
     
   .NET Install Tool, .NET Extension Pack을 설치합니다.
     
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/455d028f-b39e-4b28-92cb-376fba1a1111)  

3. NuGet Package Manager 설치하기  <br>
     
   NuGet Package Manager를 확장에서 검색해 설치합니다.
     
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/9e33e0eb-8c26-42e9-b54b-2d7a0fd0edee)  

4. C# 관련 확장 설치하기 <br>  
  C# Dev Kit, C#을 확장에서 설치합니다.
  
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/2cfd5875-c919-4e89-836b-ea6ed6015bdf)

<br>
<br>  

## 3. polyglot 노트북 실행하기  
  
➤[Polyglot 노트북 다운받기](https://github.com/pmj-chosim/Vision_Odessy_Guide/blob/main/VisionAIDemo.ipynb)   

위 링크에서 polyglot 노트북 파일을 다운 받습니다.  
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/14f9b64d-cbd5-4db2-b8c1-a6285457b355)  

Visual Studio Code에서 파일 > 파일 열기 를 클릭해, 다운받은 polyglot 노트북을 선택합니다.  
  
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/ca856d20-5d9a-4589-8871-45576fc395f6)  
.NET Interactive를 선택합니다.  

![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/156b1a33-2c9f-4ca0-aa3d-a2f51be1eabe)  
동그라미 부분을 클릭한 후, csharp을 선택합니다.  

<br>
<br>
  
[MS AI Odessy Vision Solution 가이드 ](https://learn.microsoft.com/ko-kr/training/challenges?id=ac42a113-3959-4e04-ba27-328567df7051&WT.mc_id=cloudskillschallenge_ac42a113-3959-4e04-ba27-328567df7051&ocid=Odyssey24_csc_fsi_India_wwl) 문서를 참고하며 polyglot 노트북을 함께 실행합니다.  
<br>
<br>

※ polyglot 노트북에서 코드 실행하는 방법
  
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/a12adf03-b790-43b2-9d48-ac945d387909)  
  
▷ 버튼을 누르면 해당 블록의 코드를 실행할 수 있습니다.
  
<br>  
<br> 

※ polyglot 노트북에서 수정이 필요한 부분  
  
* 사용할 이미지의 주소
  본인 컴퓨터에서의 이미지 주소로 대체합니다.   
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/7ee426f6-902e-4357-905e-bb0459d2569b)

* API 인증
  본인의 API 키와 엔드포인트로 수정합니다.  
![image](https://github.com/pmj-chosim/Vision_Odessy_Guide/assets/114579651/ab2a8e8c-6b64-4acf-8d75-f3104d46bca8)
