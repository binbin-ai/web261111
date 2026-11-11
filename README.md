<div style="max-width: 800px; margin: 0 auto; font-family: 'Pretendard', sans-serif; color: #333;">
  <!-- 헤더 섹션 -->
  <div style="border-bottom: 2px solid #20c997; padding-bottom: 10px; margin-bottom: 30px;">
    <h1 style="color: #12b886; font-size: 2em; margin-bottom: 5px;">[오늘의 개발 일기] DevOps와 DOM</h1>
</div>

  <!-- DevOps & CI/CD 섹션 -->
  <h2 style="color: #343a40; margin-top: 40px; border-left: 4px solid #20c997; padding-left: 10px;">DevOps와 CI/CD</h2>
  
  <blockquote style="background: #f8f9fa; border-left: 4px solid #adb5bd; padding: 15px 20px; margin: 15px 0; border-radius: 0 8px 8px 0;">
    <strong style="color: #212529; font-size: 1.1em;">DevOps (데브옵스)</strong><br>
    <span style="line-height: 1.6; color: #495057;">단순한 기술 스택이 아니라, <b>개발(Dev)에서 배포 환경(Ops)으로 이어지는 흐름을 원만하게 만들려는 철학이자 조직 문화</b>다. 우리가 로컬에서 작업한 코드를 Git으로 추적하고 GitHub로 연동해 호스팅했던 그 일련의 과정들이 바로 DevOps의 기초</span>
  </blockquote>
  
  <p style="line-height: 1.8; color: #495057;">
    이러한 DevOps의 철학을 <strong>실제로 자동화하여 구현하는 방법</strong>이 바로 <b>CI / CD</b>(지속적 통합 / 지속적 배포)다. 매번 수동으로 파일을 올리고 서버를 재시작하는 배포 과정을 자동화하면, 개발자는 온전히 코드 작성에만 집중할 수 있게 된다.
  </p>

  <!-- DOM 섹션 -->
  <h2 style="color: #343a40; margin-top: 40px; border-left: 4px solid #20c997; padding-left: 10px;">DOM과 JavaScript: 문서를 동적으로</h2>
  
  <p style="line-height: 1.8; color: #495057;">
    정적인 HTML 문서를 동적으로 변환해 주는 것이 바로 <strong>DOM (Document Object Model)</strong>이다. 
    브라우저가 HTML 문서를 객체(Object) 형태로 모델링하여, 자바스크립트가 이를 동적으로 조작하고 변경할 수 있게 해주는 중요한 뼈대 역할을 한다.
  </p>

  <!-- 코드 블록 스타일링 -->
  <div style="background: #282c34; color: #abb2bf; padding: 20px; border-radius: 8px; font-family: 'Courier New', Courier, monospace; font-size: 0.95em; line-height: 1.5; margin-top: 15px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
    <span style="color: #7f848e; font-style: italic;">// 1. 문서의 id, class등의 요소를 선택하는 메서드</span><br>
    <span style="color: #e5c07b;">document</span>.<span style="color: #61afef;">querySelector</span>(<span style="color: #98c379;">'.my-class'</span>);<br><br>
    <span style="color: #7f848e; font-style: italic;">// 2. 찾아낸 부모 요소 안에 새로운 자식 요소를 추가하는 메서드</span><br>
    <span style="color: #e5c07b;">element</span>.<span style="color: #61afef;">appendChild</span>(<span style="color: #e06c75;">newElement</span>);
  </div>
 
</div>