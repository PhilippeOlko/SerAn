# Sery Kraftowe – przykładowa strona zamówień

## Uruchomienie lokalnie

1. Stwórz nowy projekt Next.js (npx create-next-app@latest).
2. Skopiuj pliki z katalogów `src/data/`, `src/components/`, `pages/`, `public/styles/` do projektu.
3. Dodaj zdjęcia do `public/images/` (np. cheese5.jpg, cheese6.jpg, cheese7.jpg, cheese8.jpg).
4. Dodaj globalny styl do `_app.tsx`:

```tsx
// _app.tsx
import '../public/styles/global.css';
export default function App({ Component, pageProps }) {
  return <Component {...pageProps} />;
}
```

5. Uruchom stronę:  
   `npm run dev` lub `yarn dev`

6. Wejdź na [http://localhost:3000](http://localhost:3000) i zobacz przykładową stronę!

## Edycja produktów

Edytuj `src/data/products.ts`, dodając kolejne sery, ceny, zdjęcia, jednostki.

---

**Chcesz dodać więcej funkcji, sekcje lub design? Daj znać!**
