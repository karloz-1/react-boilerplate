# React Template
Template para proyectos de react lista para usar y desarrollar | **out-of-the-box**

## Uso

1. Clonar el repositorio
2. Colocar el comando: `npm install`
3. Desarrollar

> [!Note]
> Si quieres implementar esta plantilla automatizada con un solo comando que hace todos los pasos y además hace unas funciones extras bastante utiles, mira este repo: **Pronto**

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