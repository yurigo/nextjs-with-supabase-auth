# Ejemplo: Supabase authentication client- and server-side (API routes), and SSR with auth cookie.

Basado en el ejemplo: [supabase/examples/nextjs-with-supabase-auth](https://github.com/supabase/supabase/tree/master/examples/nextjs-with-supabase-auth)

> This example shows how to use Supabase auth both on the client and server in both [API routes](https://nextjs.org/docs/api-routes/introduction) and when using [server side rendering (SSR)](https://nextjs.org/docs/basic-features/pages#server-side-rendering). This example uses helper functions that can be viewed at [supabase auth helpers repository](https://github.com/supabase-community/supabase-auth-helpers).



## Deploy with Vercel

> ~~The Vercel deployment will guide you through creating a Supabase account and project. After installation of the Supabase integration, all relevant environment variables will be set up so that the project is usable immediately after deployment 🚀~~


Al intentar desplegar este ejemplo en Vercel fallaba.  Desconozco el motivo.

He creado este repositorio y he desplegado la aplicación a mano:

En Vercel:

1.  `+ New project`

![1](https://user-images.githubusercontent.com/5684699/158981091-d3ded437-991e-4190-ba56-422da403d0c1.PNG)

> * Si no tienes cuenta asociada a github.  `+ Add GitHub Account`
> 
> ![1 1](https://user-images.githubusercontent.com/5684699/158981119-48f07bbb-49e7-4500-87fd-aea191660667.png)
> 
> * En GitHub, dar acceso a Vercel:
> 
> ![1 2](https://user-images.githubusercontent.com/5684699/158981135-97e2cfde-cf61-4dda-98f0-bfba812c1da1.PNG)
> 

2. Importar un repositorio

![2](https://user-images.githubusercontent.com/5684699/158981149-c4830a41-a8f0-4ed0-b23d-ebc89be97d2d.PNG)

3. Configurar el proyecto, en este caso las variables de entorno. (Se deberían encontrar en `supabase -> settings -> API` )

> * SUPABASE_URL corresponde a `Configuration URL` de supabase
> 
> ![supabase_url](https://user-images.githubusercontent.com/5684699/158981224-c8625845-2b83-4ed8-844c-24474d8c6b30.PNG)
> 
> * SUPABASE_KEY corresponde a `Project API keys anon public` de supabase
> ![supabase_key](https://user-images.githubusercontent.com/5684699/158981212-9b7f5726-d49f-439c-bf8d-d9bbdde3eaba.PNG)
> 

4. `Deploy`

![deploy](https://user-images.githubusercontent.com/5684699/158981241-83beff73-1edc-41f1-af82-a4b5c0ebed69.PNG)

5. Espera a que se compile...

![wait](https://user-images.githubusercontent.com/5684699/158981283-c8b1a126-ab99-459a-a55e-7b16bd9cb343.png)

6. Profit

![profit](https://user-images.githubusercontent.com/5684699/158981312-ea9c21e5-fa5d-42e5-8662-f817392d8fd6.PNG)




