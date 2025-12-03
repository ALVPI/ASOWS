# 🖥️ Directorio Activo - Windows Server 2022

Práctica de Administración de Sistemas Operativos donde se implementa un entorno completo de directorio activo con Windows Server 2022, integrando sistemas Windows y Linux.

## 🎯 Objetivos
- Instalar y configurar Windows Server 2022
- Implementar Active Directory Domain Services (AD DS)
- Configurar servicios DNS y Hyper-V
- Integrar Windows 11 y Ubuntu en el dominio
- Configurar enrutamiento y acceso remoto

## 🔧 Tecnologías
- Windows Server 2022
- Active Directory Domain Services
- DNS Server
- Hyper-V (virtualización anidada)
- TinyWin11 y Ubuntu 22.04
- RAS (Remote Access Service)

## 📋 Pasos Principales
1. Instalación WS2022 en Proxmox con drivers VirtIO
2. Configuración inicial: red, RDP (puerto 22), firewall
3. Instalación Hyper-V e importación de VMs
4. Configuración red interna 192.168.96.0/24
5. Instalación AD DS y creación dominio ad-aso96.lab
6. Configuración DNS con zonas directa/inversa
7. Unión de TinyWin11 y Ubuntu al dominio
8. Instalación RAS para enrutamiento NAT

## ✅ Resultados
- Dominio activo operativo: ad-aso96.lab
- Autenticación centralizada en Windows/Linux
- Resolución DNS interna funcional
- Acceso remoto RDP/SSH habilitado
- Enrutamiento NAT para acceso a Internet
