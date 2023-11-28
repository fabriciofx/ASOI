---
marp: true
theme: gaia
backgroundColor: white
color: black
paginate: true
footer: Administração de Sistemas Operacionais I - Fabrício Barros Cabral <<fabricio.cabral@ead.ifpe.edu.br>>
---
<style>
img[alt~="center"] {
    display: block;
    margin: 0 auto;
}
</style>

<!-- _paginate: false -->
# **Administração de Sistemas Operacionais I (ASOI)**

## Aula 3 - Sistemas de Arquivos

---

## Introdução

- O Windows Server 2022 suporta vários sistemas de arquivos para atender a diferentes necessidades e cenários de uso
- O suporte a esses sistemas de arquivos oferece flexibilidade aos administradores de sistema para escolher o sistema mais adequado às suas necessidades de armazenamento, segurança e integridade de dados

---

## NTFS (New Technology File System)

- É o sistema de arquivos padrão para o Windows Server e oferece recursos avançados, como suporte a permissões de acesso, criptografia, compressão, cotas de disco, entre outros
- É altamente confiável e usado em ambientes corporativos devido à sua robustez e segurança

---

## Características do NTFS

- Segurança Avançada: Suporta um sistema robusto de permissões de arquivo e pasta, permitindo que os administradores controlem quem pode acessar, ler, gravar ou modificar determinados arquivos
- Criptografia de Arquivos: Oferece suporte à criptografia de arquivos individuais usando o recurso BitLocker, garantindo a proteção dos dados sensíveis.

---

## Características do NTFS

- Recuperação de Dados e Confiabilidade: Usa um sistema de journaling para registrar operações de gravação antes de executá-las, o que melhora a integridade dos dados e facilita a recuperação em caso de falhas inesperadas
- Verificação e Correção de Erros: Implementa mecanismos para verificar e corrigir erros no sistema de arquivos, garantindo a integridade dos dados armazenados
- Recursos Avançados: Oferece a capacidade de compactar arquivos e pastas para economizar espaço em disco, especialmente útil para arquivos de texto e documentos

---

## Características do NTFS

- Cotas de Disco: Permite aos administradores limitar o espaço em disco disponível para usuários ou grupos específicos.
- Suporte a Arquivos de Tamanho Grande: O NTFS suporta arquivos individuais de tamanho muito grande (teoricamente até 16 exabytes) e volumes de grande capacidade (256 terabytes), oferecendo flexibilidade para ambientes de armazenamento de dados extensos

---

## Características do NTFS

- Recuperação de Sistema (Pontos de Verificação - System Restore): Permite criar pontos de verificação do sistema que podem ser usados para restaurar o sistema para um estado anterior em caso de problemas
- Recursos de Indexação e Pesquisa: O NTFS oferece recursos de indexação avançados, permitindo pesquisas rápidas e eficientes dentro do sistema de arquivos

---

## ReFS (Resilient File System)

- É um sistema de arquivos mais recente da Microsoft, projetado para oferecer maior resiliência e proteção contra falhas
- Ele é otimizado para volumes de grande capacidade e fornece verificação de dados em segundo plano para detectar e corrigir corrupções

---

## FAT32 (File Allocation Table)

- O FAT32 é um sistema de arquivos mais antigo e menos usado em ambientes corporativos devido a limitações, como tamanho máximo de arquivo (4 gigabytes) e volume (2 terabytes)
- No entanto, ainda é compatível com o Windows Server 2022 para compatibilidade com dispositivos mais antigos

---

## exFAT (Extended File Allocation Table)

- O exFAT é um sistema de arquivos otimizado para suportar arquivos grandes e é amplamente utilizado em dispositivos de armazenamento removíveis, como unidades flash USB e cartões de memória
- Oferece suporte a arquivos maiores que o FAT32 e não tem as limitações desse sistema
- Os limites de tamanho máximo de arquivo é de 16 exabytes e de volume de 128 petabytes

---

## SMB (Server Message Block)

- Embora não seja um sistema de arquivos em si, o SMB é um protocolo de compartilhamento de arquivos utilizado pelo Windows para acessar e compartilhar recursos de armazenamento de rede
- O Windows Server 2022 oferece suporte ao SMB para compartilhamento de arquivos e impressoras na rede
