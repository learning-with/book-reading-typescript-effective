# 이펙티브 타입스크립트
- 저자 : 댄 밴더캄
- 동작 원리의 이해와 구체적인 조언 62가지 

## 스터디
<table>
  <tr>
    <td align="center" width="92px">
      <a href="https://github.com/a-honey" target="_blank">
       <img src="https://github.com/learning-with/learning-react/assets/75254185/6e087fa7-dd77-4353-9643-a4b9c081d958" alt="마님 프로필"/>
      </a>
    </td>
    <td align="center" width="92px">
      <a href="https://github.com/hyeb-in" target="_blank">
        <img src="https://github.com/learning-with/learning-js/assets/101353408/9d690924-d984-4eca-a5c8-45872a7344ca" alt="굉스터 프로필" />
      </a>
    </td>
    <td align="center" width="92px">
      <a href="https://github.com/devchaeyoung target="_blank">
        <img src="https://avatars.githubusercontent.com/u/124546770?v=4" alt="진채영 프로필" />
      </a>
    </td>
    <td align="center" width="92px">
      <a href="https://github.com/LCGechk0311" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/134675465?v=4" alt="창근 프로필" />
      </a>
    </td>
        <td align="center" width="92px">
      <a href="https://github.com/he110-wOrld" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/134676310?s=400&u=34078b40b72196dac4999fd8c15d084a73b691a2&v=4" alt="지호 프로필" />
      </a>
    </td>
     <td align="center" width="92px">
      <a href="https://github.com/hamo-o" target="_blank">
        <img src="https://github.com/hamo-o.png?width=200px" alt="햄 프로필" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/a-honey" target="_blank">
        마님
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/hyeb-in" target="_blank">
        굉스터
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/devchaeyoung" target="_blank">
        진채영
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/LCGechk0311" target="_blank">
        창근
      </a>
    </td>
        </td>
     <td align="center">
      <a href="https://github.com/ji-hoood" target="_blank">
        지호
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/hamo-o" target="_blank">
        햄
      </a>
    </td>
  </tr>
</table>

# 목차
#### 1. 타입스크립트 알아보기
- 아이템1. 타입스크립트와 자바스크립트의 관계 이해하기
- 아이템2. 타입스크립트 설정 이해하기
- 아이템3. 코드 생성과 타입이 관계없음을 이해하기
- 아이템4. 구조적 타이핑에 익숙해지기
- 아이템5. any 타입 지양하기

#### 2. 타입스크립트의 타입 시스템
- 아이템6. 편집기를 사용하여 타입 시스템 탐색하기
- 아이템7. 타입이 값들의 집합이라고 생각하기
- 아이템8. 타입 공간과 값 공간의 심벌 구분하기
- 아이템9. 타입 단언보다는 타입 선언을 사용하기
- 아이템10. 객체 래퍼 타입 피하기
- 아이템11. 잉여 속성 체크의 한계 인지하기
- 아이템12. 함수 표현식에 타입 적용하기
- 아이템13. 타입과 인터페이스의 차이점 알기
- 아이템14. 타입 연산과 제너릭 사용으로 반복 줄이기
- 아이템15. 동적 데이터에 인덱스 시그니처 사용하기
- 아이템16. number 인덱스 시그니처보다는 Array, 튜플, ArrayLike를 사용하기
- 아이템17. 변경 관련된 오류 방지를 위해 readonly 사용하기
- 아이템18. 매핑된 타입을 사용하여 값을 동기화하기

 #### 3. 타입 추론
- 아이템19. 추론 가능한 타입을 사용해 장황한 코드 방지하기
- 아이템20. 다른 타입에는 다른 변수 사용하기
- 아이템21. 타입 넓히기
- 아이템22. 타입 좁히기
- 아이템23. 한꺼번에 객체 생성하기
- 아이템24. 일관성 있는 별칭 사용하기
- 아이템25. 비동기 코드에는 콜백 대신 async 함수 사용하기
- 아이템26. 타입 추론에 문맥이 어떻게 사용되는지 이해하기
- 아이템27. 함수형 기법과 라이브러리로 타입 흐름 유지하기

#### 4. 유효한 상태만 표현하는 타입을 지향하기
- 아이템28. 유효한 상태만 표현하는 타입을 지향하기
- 아이템29. 사용할 때는 너그럽게, 생성할 때는 엄격하게
- 아이템30. 문서에 타입 정보를 쓰지 않기
- 아이템31. 타입 주변에 null 값 배치하기
- 아이템32. 유니온의 인터페이스보다는 인터페이스의 유니온을 사용하기
- 아이템33. string 타입보다 더 구체적인 타입 사용하기
- 아이템34. 부정확한 타입보다는 미완성 타입을 사용하기
- 아이템35. 데이터가 아닌, API와 명세를 보고 타입 만들기
- 아이템36. 해당 분야의 용어로 타입 이름 짓기
- 아이템37. 공식 명칭에는 상표를 붙이기

#### 5. any 다루기
- 아이템38. any 타입은 가능한 한 좁은 범위에서만 사용하기
- 아이템39. any를 구체적으로 변형해서 사용하기
- 아이템40. 함수 안으로 타입 단언문 감추기
- 아이템41. any의 진화를 이해하기
- 아이템42. 모르는 타입의 값에는 any 대신 unknown을 사용하기
- 아이템43. 몽키 패치보다는 안전한 타입을 사용하기
- 아이템44. 타입 커버리지를 추적하여 타입 안전성 유지하기
#### 6. 타입 선언과 @types
- 아이템45. devDependencies에 typesctipt와 @types 추가하기
- 아이템46. 타입 선언과 관련된 세 가지 버전 이해하기
- 아이템47. 공개 API에 등장하는 모든 타입을 익스포트하기
- 아이템48. API 주석에 TSDocs 사용하기
- 아이템49. 콜백에서 this에 대한 타입 제공하기
- 아이템50. 오버로딩 타임보다는 조건부 타입을 사용하기
- 아이템51. 의존성 분리를 위해 미러 타입을 사용하기
- 아이템52. 테스팅 타입의 함정에 주의하기
#### 7. 코드를 작성하고 실행하기
- 아이템53. 타입스크립트 기능보다는 ECMAScript 기능을 사용하기
- 아이템54. 객체를 순회하는 노하우
- 아이템55. DOM 계층 구조 이해하기
- 아이템56. 정보를 감추는 목적으로 private 사용하지 않기
- 아이템57. 소스맵을 사용하여 타입스크립트 디버깅하기
#### 8. 타입스크립트로 마이그레이션하기
- 아이템58. 모던 자바스크립트로 작성하기
- 아이템59. 타입스크립트 도입 전에 @ts-check와 JSDoc으로 시험해 보기
- 아이템60. allowJs로 타입스크립트와 자바스크립트 같이 사용하기
- 아이템61. 의존성 관계에 따라 모듈 단위로 전환하기
- 아이템62. 마이그레이션의 완성을 위해 nolmplicitAny 설정하기
