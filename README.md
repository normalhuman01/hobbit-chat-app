### Hobbit Chat: React 4 Immersion

<hr>

#### Class 1 - Creating our project

##### Manual Setup
[getting-started](https://nextjs.org/docs/getting-started)

```
yarn init -y
```

```
yarn add next react react-dom
```

[coolors.co](https://coolors.co/)


```
yarn add @skynexui/components
```

```
npx gitignore node
```

<hr>

#### Class 02 - State, new pages and SPA vs Traditional navigation

[custom-app](https://nextjs.org/docs/advanced-features/custom-app)

<hr>

#### Class 03 - Offline chat? Improving your skills with State

<hr>

#### Class 04 - Integrating with Supabase
* [supabase](https://supabase.com/)
* [api.github](https://api.github.com/users/lucasrmagalhaes)

```javascript
fetch('https://api.github.com/users/lucasrmagalhaes')
.then(async (respostaDoServidor) => {
    const respostaEsperada = await respostaDoServidor.json();
    console.log(respostaEsperada);
})
```

* [supabase-js](https://github.com/supabase/supabase-js)

```
yarn add @supabase/supabase-js
```

```js
supabaseClient
    .from('tabela')
    .select('*')
    .then((dados) => {
        console.log('Dados da consulta: ', dados);
    });

```

<hr>

#### Classroom 05 - Adding support for Stickers

<hr>

#### ENV
```
NEXT_PUBLIC_BG
```

```
SUPABASE_URL
```

```
SUPABASE_ANON_KEY
```

```
NEXT_PUBLIC_SMEAGOL
```
