# React Template

## Stack:
- React
- Tailwind

## utils
### cn (classNames)
Esta función es para pasar contenido en el className de los componentes sin problema.

Ejemplo de uso:
```jsx
// H1.jsx
import { cn } from "../utils/cn";

export const H1 = ({ children, className }) => {
  return (
    <h1 className={cn("text-3xl font-bold text-blue-500", className)}>
      {children}
    </h1>
  );
};
```