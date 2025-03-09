# React - 19 + Vite + Tailwind - 4

1. npm create vite@latest my-react-app -- --template react
2. cd my-react-app
3. npm install tailwindcss @tailwindcss/vite
4. vite.config.ts ( add 2 Files to vite)

    import tailwindcss from '@tailwindcss/vite',
    tailwindcss(),
    Example : 
        import { defineConfig } from 'vite'
        import react from '@vitejs/plugin-react'
        import tailwindcss from '@tailwindcss/vite'

        export default defineConfig({
        plugins: [
            tailwindcss(),
            react()
        ],
        })

5. index.css add css ( @import "tailwindcss";)
6. npm run dev
