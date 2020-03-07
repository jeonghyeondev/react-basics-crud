# React Basics CRUD
리액트(기초) 프로젝트 저장소입니다.

### `react-form-crud`
CRUD(Create Read Update Delete) Form Tag를 사용하여 진행한 리액트(기초) 프로젝트입니다.
    1. Form Tag (creat, update, delete)
    2. Sass
    3. props
        - 컴포넌트 내부의 `Immutable Data`
        - JSX 내부에 `{ this.props.propsName }`
        - 컴포넌트를 사용 할 때, <>괄호 안에 `propsName="value"`
    4. state
        - 유동적인 데이터
        - JSX 내부에 `{ this.state.stateName }`
        - 초기값 설정이 필수, 생성자(constructor)에서 `this.state={}`으로 설정 값을 수정 할 때에는 `this.setState({ … })`, <br />렌더링 된 다음에 `this.state` = 절대 사용하지 말것


