# React & Redux State Architecture

A technical repository focused on advanced state management patterns within the React ecosystem. This collection documents the implementation of predictable state containers, data flows, and complex UI synchronizations using **Redux** and **React-Redux**.

## Architectural Concepts
- **Single Source of Truth:** Centralizing application state to ensure data consistency across disconnected components.
- **Immutability:** Mastering state updates via pure functions (Reducers) to enable time-travel debugging and predictable renders.
- **Unidirectional Data Flow:** Implementing the classic `Action -> Reducer -> Store -> View` cycle.
- **Middleware Integration:** Handling side effects and asynchronous logic (e.g., using Redux Thunk).

## Laboratory Modules

| Module Group | Focus Area | Technical Objective |
| :--- | :--- | :--- |
| **redux_practise 1-8** | Core Redux | Mastering the store, dispatching actions, and writing complex reducers in Vanilla JS. |
| **react_redux_practise** | Integration | Utilizing `Provider`, `connect()`, and modern hooks like `useSelector` and `useDispatch`. |

## Key Learning Milestones
- **Redux Toolkit (RTK):** Development with `createSlice` and `configureStore` to reduce boilerplate.
- **Normalized State:** Structuring data to avoid deep nesting and improve lookup performance.
- **Asynchronous Actions:** Integrating API calls into the Redux workflow for a unified data layer.

## Installation
1. Clone the repository:
   ```bash
   git clone [https://github.com/TiffanyNels/React_and_Redux.git](https://github.com/TiffanyNels/React_and_Redux.git)
