<div align="center">
   <img src="https://raw.githubusercontent.com/suyashvsingh/rce70-client/main/public/images/logo.png" alt="Logo" height="80">
</div>

<h3 align="center">
  <a href="https://rce70.vercel.app/">
      RCE70
  </a>
</h3>

### Installation

1. Make sure Minikube and _kubectl_ are installed

2. Clone the repo
   ```sh
   git clone https://github.com/suyashvsingh/rce70-k8s.git
   ```

3. Run the command
   ```sh
   kubectl apply -f rce70-server.yaml -f rce70-client.yaml
   ```

4. Run the command
   ```sh
   minikube service list
   ```
   
5. Click on the URL corresponding to the service _rce70-client_. Application will open on a new browser window

## Multiple language support

![javascript]
![python]
![c++]
![c]
![java]

## Team 😃

Made with love by:

1. Sanket Diwate
2. Ketan Prakash
3. Aditya Pote
4. Suyash Vikram Singh

[c++]: https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white
[c]: https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white
[python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[javascript]: https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E
[java]: https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white
