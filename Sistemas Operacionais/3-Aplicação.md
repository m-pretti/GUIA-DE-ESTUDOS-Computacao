# Aplicações e Funcionamento Interno

O **kernel** é o núcleo do sistema operacional, responsável por intermediar o uso do hardware e fornecer serviços básicos para os programas.

---

## Componentes principais

### 1. Processadores (CPUs)
- Executam instruções e alternam entre **modo usuário** e **modo núcleo**.  
- O kernel gerencia mudanças de contexto, escalonamento e chamadas de sistema (system calls).  

### 2. Memória
- **RAM**: área de trabalho dos programas em execução.  
- **Cache**: memória ultrarrápida próxima à CPU.  
- **Memória virtual**: permite rodar programas maiores que a RAM, movendo dados entre disco e memória principal.  

### 3. Armazenamento
- **HDDs e SSDs**: guardam dados a longo prazo.  
- O SO abstrai esses dispositivos na forma de **sistema de arquivos**.  

### 4. Dispositivos de Entrada/Saída
- Teclados, monitores, impressoras, mouses.  
- Controlados por **drivers** que conversam diretamente com o kernel.  

### 5. Barramentos
- Caminhos de comunicação (PCIe, USB, SATA) que conectam CPU, memória e periféricos.  

---

## Segurança

- **Modo usuário vs. modo núcleo**: garante que programas comuns não interfiram no hardware.  
- **System calls**: interface segura para que programas acessem serviços privilegiados.  
- O SO protege memória, arquivos e dispositivos de acessos indevidos.
