## JSX 링크로 라우팅 이동하기

### 네비게이션 링크

```jsx
<NavLink>
activeClassName: string
activeStyle: object
exact: bool
strict: bool
isActive: func
location: object
airia-current: string
```

- import {NavLink} from 'react-router-dom';
- activeClassName, activeStyle 처럼 active 상태에 대한 스타일 지정이 가능하다.
  -Router의 path처럼 동작하기 때문에 exact가 있다.

## Redirect

```jsx
import { Redirect } from "react-router-dom";

//jsx
<Redirect to="/" />;
```
