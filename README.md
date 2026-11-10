# 05-notehub

NoteHub — застосунок для зберігання, створення, видалення та пошуку нотаток на React і TypeScript. Дані зберігаються на бекенді [NoteHub API](https://notehub-public.goit.study/api/docs), запитами керує TanStack Query, форма створення нотатки побудована на Formik і Yup, пошук відкладений через use-debounce, пагінація — React Paginate.

## Запуск

1. Встановіть залежності: `npm install`.
2. Створіть файл `.env.local` у корені проєкту і додайте свій токен NoteHub:

   ```
   VITE_NOTEHUB_TOKEN=ваш_токен
   ```

3. Запустіть застосунок: `npm run dev`.

## Скрипти

- `npm run dev` — запуск у режимі розробки
- `npm run build` — збірка
- `npm run lint` — перевірка лінтером
- `npm run format` — форматування коду Prettier
