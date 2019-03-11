## 0.0.1 ~ 0.0.2
### init ver.

## 0.0.3
### 1. Added missing type.
```typescript
function VTComponents(vt_opts: vt_opts): TableComponents
```
### 2. Some bugs fixed.

## 0.0.4
### 1. Solve the initial rendering bug. ([#1](https://github.com/wubostc/virtualized-table-for-antd/issues/1 "能有个完整的demo吗"))

### 2. Update the README.md

## 0.0.5
### 1. add new API VTRefresh
```typescript
export declare function VTRefresh(id: number): void;
```
### 2. remove the func shouldComponentUpdate of VTWrapper
### 3. remove the func shouldComponentUpdate of VTRow