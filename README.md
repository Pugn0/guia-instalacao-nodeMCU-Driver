# 🚀 Instalando o Driver do NodeMCU e ESP32

## 📌 Introdução

Tanto a placa **NodeMCU** quanto a **ESP32** utilizam um conversor **USB-Serial** para viabilizar a comunicação entre o computador e o chip **ESP8266/ESP32**. Dependendo da versão da placa, o chip pode ser:

- `CP210x` → NodeMCU V2 e ESP32  
- `CH340G` → NodeMCU V3  

Neste guia, você aprenderá como instalar o driver adequado para garantir que sua placa seja reconhecida corretamente e possa ser programada com sucesso.

---

## 📸 Imagens das Placas

- **NodeMCU ESP8266 V2**  
  ![V2](https://www.robocore.net/tutoriais/upload/tutoriais/163_img_9_M.png)

- **NodeMCU ESP8266 V3**  
  ![V3](https://www.robocore.net/tutoriais/upload/tutoriais/163_img_10_M.png)

---

## 🧪 Verificando se o Driver é Instalado Automaticamente

Conecte a placa ao seu computador usando um cabo **Micro USB**.  
O sistema operacional tentará instalar o driver automaticamente. Caso não consiga, será necessário instalar manualmente.

🔍 Se não for detectado, o Gerenciador de Dispositivos mostrará um item com erro, como na imagem abaixo:

![Sem driver](https://www.robocore.net/upload/tutoriais/163_img_8_H.png)

---

## 🛠️ Instalação do Driver CP210x (NodeMCU V2 / ESP32)

### 🔗 Links para Download

- [Windows](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CP210x_Windows_Drivers.zip)  
- [Mac OSX](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CP210x_Mac_OSX_VCP_Driver.zip)  
- [Linux 2.6.x](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CP210x_Linux_2.6.x_VCP_Driver_Source.zip)  
- [Linux 3.x.x](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CP210x_Linux-3-x-x-VCP-Driver-Source.zip)

### 🖥️ Instalação no Windows

1. Extraia os arquivos `.zip` baixados.
2. Execute o instalador correspondente à versão do seu sistema (32 ou 64 bits) como **Administrador**:
   - Clique com o botão direito no instalador → `Executar como administrador`.

![Instalador](https://www.robocore.net/upload/tutoriais/163_img_1_H.png)

3. Siga o processo de instalação.

![Instalado com sucesso](https://www.robocore.net/upload/tutoriais/163_img_3_H.png)

✅ **Pronto!** Sua placa está pronta para uso.

---

## 🛠️ Instalação do Driver CH340G (NodeMCU V3)

### 🔗 Links para Download

- [Windows](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CH341SER_WINDOWS.zip)  
- [Mac OSX](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CH341SER_MAC.ZIP)  
- [Linux](https://s3-sa-east-1.amazonaws.com/robocore-tutoriais/163/CH341SER_LINUX.ZIP)

### 🖥️ Instalação no Windows

1. Extraia os arquivos `.zip`.
2. Execute o instalador como **Administrador** e clique em `INSTALL`.

![Instalador CH340G](https://www.robocore.net/upload/tutoriais/163_img_6_H.png)

3. Após concluir, clique em `OK`.

![Instalação concluída](https://www.robocore.net/upload/tutoriais/163_img_7_H.png)

✅ **Pronto!** A placa está pronta para comunicação.

---

## 🔌 Descobrindo a Porta COM da Placa

Após conectar sua placa, acesse o **Gerenciador de Dispositivos** do Windows para identificar a **porta COM** atribuída:

![Porta COM](https://www.robocore.net/upload/tutoriais/163_img_5_H.png)

---

## 📦 Continuando...

Agora que o driver está instalado corretamente, você pode configurar a **Arduino IDE** para programar seu NodeMCU ou ESP32.  
👉 [Clique aqui para aprender como configurar a IDE](#)

---

## 🧠 Créditos

Este tutorial foi baseado nos guias da [RoboCore](https://www.robocore.net/tutoriais/instalando-driver-do-nodemcu).

---

## ⚙️ Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

