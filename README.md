# Exposing Localhost to the Internet using Ngrok.

---


First of all we need to install [ngrok](https://ngrok.com/download)

You can expose anything like a simple website, tcp client server chat etc.................

I'll expose a simple html page.

---

We are gonna use python3 to start a server locally.

---

<img width="909" alt="Screenshot 2024-08-10 at 6 22 29 PM" src="https://github.com/user-attachments/assets/fcc1575b-3341-4dda-8fc4-14613544e12c">

---

Here we can see our web page is running locally.

<img width="1384" alt="Screenshot 2024-08-10 at 6 23 58 PM" src="https://github.com/user-attachments/assets/d3f6f7c5-a769-4a42-8348-8408117166c0">

---

Keep the local server on.

open up another terminal on the same directory location.

Now we have to set authentication token for ngrok.

go to [here](https://dashboard.ngrok.com/signup) register an acoount. and you get your auth token....

To set auth token.

in the terminal type

```
ngrok config add-authtoken your-auth-token
```

Now you are ready to use ngrok..

in the terminal type```ngrok http port no. in my case it's 9191```

```
ngrok http 9191
```
---
<img width="1385" alt="Screenshot 2024-08-10 at 6 31 48 PM" src="https://github.com/user-attachments/assets/96024a05-78ec-45a8-8641-b024df6dbc14">

---
Visit the web interface address.

<img width="915" alt="Screenshot 2024-08-10 at 6 34 39 PM" src="https://github.com/user-attachments/assets/65256c4e-17b8-4ec4-8f74-526d3e748fb3">

click on the link..then visit site.......

<img width="915" alt="Screenshot 2024-08-10 at 6 34 39 PM" src="https://github.com/user-attachments/assets/48d63c2b-c0e4-4d20-83b9-f4c001002a58">


<img width="913" alt="Screenshot 2024-08-10 at 6 34 49 PM" src="https://github.com/user-attachments/assets/29f4d412-65b8-40b4-8104-9637934d55b9">

Now you can visit the Forwarding address to access the web page from anywhere in world.............

<img width="1440" alt="Screenshot 2024-08-10 at 6 35 22 PM" src="https://github.com/user-attachments/assets/ce613a01-4521-4a7f-b222-442f24e0fc08">


---



