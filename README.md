# Ejemplo: Supabase authentication client- and server-side (API routes), and SSR with auth cookie.

Basado en el ejemplo: [supabase/examples/nextjs-with-supabase-auth](https://github.com/supabase/supabase/tree/master/examples/nextjs-with-supabase-auth)

> This example shows how to use Supabase auth both on the client and server in both [API routes](https://nextjs.org/docs/api-routes/introduction) and when using [server side rendering (SSR)](https://nextjs.org/docs/basic-features/pages#server-side-rendering). This example uses helper functions that can be viewed at [supabase auth helpers repository](https://github.com/supabase-community/supabase-auth-helpers).



## Deploy with Vercel

> ~~The Vercel deployment will guide you through creating a Supabase account and project. After installation of the Supabase integration, all relevant environment variables will be set up so that the project is usable immediately after deployment 🚀~~


Al intentar desplegar este ejemplo en Vercel fallaba.  Desconozco el motivo.

He creado este repositorio y he desplegado la aplicación a mano:

En Vercel:

1.  `  + New project`

    1. Si No tienes cuenta asociada a github.  ` + Add GitHub Account`

    2. En GitHub, dar acceso a Vercel:

2. Importar un repositorio

3. Configurar el proyecto, en este caso las variables de entorno.

    1. SUPABASE_URL
   
    2. SUPABASE_KEY

4. `Deploy`

5. Espera a que se compile...

5. Profit



