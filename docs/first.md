# 🛠 Overforged 팀 프로젝트 컨벤션

**Unity Version**: `2022.3.6f1`

---

## 📌 커밋 템플릿 (Commit Template)

|타입 (type)|설명|
|---|---|
|`feat`|새로운 기능 추가, 기존 기능을 요구사항에 맞게 수정|
|`release`|버전 릴리즈|

---

## 🌿 브랜치 규칙

- `main` 브랜치:  
    Dev 브랜치에서 하루 작업량을 **충돌 없는 상태로 merge**하여 관리
    
- **기능별 브랜치**:  
    `기능명/이니셜` 형식  
    예시: `inventory/MIN`
    

---

## 🧱 코드 컨벤션

### ✅ 네이밍 규칙

|요소|규칙|예시|
|---|---|---|
|클래스 / 인터페이스|PascalCase|`PlayerController`, `IGameService`|
|제네릭 타입|T 접두어 사용|`TEntity`, `TResult`|

> 🔗 참고: [C# 식별자 네이밍 공식 문서](https://learn.microsoft.com/ko-kr/dotnet/csharp/fundamentals/coding-style/identifier-names)

---

---

## 📦 네임스페이스 규칙

- 자신의 **이니셜을 네임스페이스**로 설정  
    예: `Player.cs` → `namespace MIN { }`
    

---

## 🔁 코루틴 규칙

- **Coroutine 변수**:  
    변수명은 `~Co` 형식  
    예: `Coroutine attackCo;`

  ![고양이 사진](go.png)
  [Main](..)


