<td style="width: 10%;">
    <img src="https://raw.githubusercontent.com/Epaminondaslage/Lab-IoT-ELE-CEFET/master/img/Logo_CEFET-MG.png" width="20%" />
</td>

### **CENTRO FEDERAL DE EDUCAÇÃO TECNOLÓGICA DE MINAS GERAIS**  
### **Departamento de Engenharia Elétrica - CEFET-MG**  
### **Coordenação do Curso de Eletrotécnica**  

### Disciplina: **PLIP - Prática de Laboratório de Instalações Prediais**
### Guia de Aula – Chave-bóia e acionamento de motobomba 

## Objetivo da Aula


## 1. Introdução

###  1. O que é uma Chave Boia?
A chave boia é um dispositivo eletromecânico, ou eletrˆnico que liga ou desliga automaticamente uma motobomba conforme o nível da água. Ela evita queima da bomba, transbordamento e funcionamento em seco.

Existem dois tipos:
- **Nível superior (caixa d’água)** — desliga a bomba quando cheia.
- **Nível inferior (cisterna/poço)** — impede funcionamento sem água.

---

##  2. Lógica das Boias

### Caixa d’água superior — NF
- Cheia → abre → bomba desliga  
- Baixa → fecha → bomba liga

### Cisterna/caixa inferior — NA
- Com água → fecha → bomba pode ligar  
- Sem água → abre → bomba desliga


## Chave-bóia para acionamento de motobomba

As bombas hidráulicas utilizadas em residências ou edifícios têm como finalidade transferir água de uma cisterna ou reservatório inferior para uma caixa d’água superior. Para garantir **comodidade**, **economia de energia** e **proteção do motor elétrico**, a bomba deve interromper seu funcionamento automaticamente nas seguintes situações:

- Quando a caixa d’água superior estiver **cheia**;
- Quando o reservatório inferior estiver **vazio**.

Para que essas condições sejam atendidas, é necessário utilizar dispositivos capazes de monitorar continuamente o nível de água nos reservatórios. Esses dispositivos de controle, conhecidos como **chave-bóia inferior** e **chave-bóia superior**, devem ser instalados **em série**, de modo que o circuito de comando da bomba seja energizado apenas quando:

- O reservatório superior estiver **vazio**, e
- O reservatório inferior estiver **cheio**.

---

## Chave-Bóia com Contato Metálico 

Este tipo de chave-bóia é composto por:

- Uma **haste** (a);
- Dois **limitadores de curso** (b);
- Uma **bóia plástica** (c);
- Um conjunto de **contatos elétricos** (d).

### Funcionamento

- À medida que o nível da água **desce**, a bóia se desloca até pressionar o limitador inferior.
- Esse movimento empurra a haste para baixo.
- Ao superar a resistência de uma mola interna, os contatos elétricos mudam de posição, permitindo **acionar ou desligar** o motor elétrico da bomba.

De forma semelhante, quando o nível da água **sobe**, a bóia pressiona o limitador superior, deslocando a haste para cima e novamente alterando a posição dos contatos elétricos conforme a condição operacional desejada.


## Chave-Bóia de Controle de Nível com Contato Reversível

A chave-bóia de controle de nível com contato reversível é um dispositivo eletromecânico utilizado para monitorar e controlar o nível de líquidos em reservatórios. Seu funcionamento baseia-se na movimentação de uma bóia que, ao acompanhar a variação do nível do líquido, aciona internamente um conjunto de contatos elétricos configurados em **modo reversível** (NA/NF).

### Características Principais

- **Bóia flutuante:** Elemento responsável por acompanhar o nível do líquido. Geralmente fabricada em material plástico resistente e impermeável.
- **Cabo flexível:** Conecta a bóia ao ponto de instalação e abriga internamente o condutor elétrico e o mecanismo de comutação.
- **Contato reversível (NA/NF):** O dispositivo possui um microinterruptor interno com um contato **normalmente aberto (NA)** e outro **normalmente fechado (NF)**, permitindo sua utilização tanto para esvaziar quanto para encher o reservatório.
- **Peso regulador:** Mantém a bóia em posição adequada para o movimento de basculamento que aciona a comutação elétrica.

### Funcionamento

O funcionamento da chave-bóia ocorre pelo **basculamento** da bóia devido à variação do nível do líquido:

1. Quando o nível do líquido **sobe**, a bóia flutua e muda sua posição angular.
2. Ao atingir o ponto de comutação, o peso interno da bóia aciona o microinterruptor, alterando o estado dos contatos:
   - O contato **NA** fecha,
   - O contato **NF** abre.
3. Quando o nível **desce**, a bóia retorna à posição oposta, invertendo novamente os contatos.

Esse comportamento permite duas aplicações distintas:

### Modo Enchimento
- O contato **NF** é usado para manter a bomba ligada enquanto o reservatório está vazio.
- Quando a água sobe e aciona a bóia, o contato abre e **desliga a bomba**.

### Modo Esvaziamento
- O contato **NA** é usado para acionar a bomba quando o reservatório está cheio.
- Quando o nível diminui e a bóia retorna, o contato abre e **desliga a bomba**.

### Resumo do Funcionamento

| Bóia     | Tipo de Contato | Estado que Fecha   | Finalidade                         |
|----------|------------------|--------------------|-------------------------------------|
| Superior | NF (Normalmente Fechado) | Caixa vazia        | Permite ligar a bomba para encher  |
| Inferior | NA (Normalmente Aberto)  | Cisterna cheia     | Impede ligar a bomba sem água      |

---

##  5. Diagrama Simples (1 Boia)

---

##  6. Diagrama Completo (2 Boias)


---

## Parte Prática

##  2. Materiais Necessários
- Motobomba
- Chave(s) boia
- Contator (recomendado acima de 1 CV)
- Disjuntor
- Cabos elétricos
- Painel elétrico opcional

---

## ⚠️ 3. Segurança
Desligue a energia antes de trabalhar. Use EPI e ferramentas isoladas.



##  7. Instalação Passo a Passo
1. Verificar tensão da boia (127/220V).
2. Fixar a boia na caixa e ajustar comprimento do cabo.
3. Instalar boia na cisterna (opcional).
4. Passar cabos em eletrodutos.
5. Ligar boias conforme o diagrama.

---

##  8. Quando usar Contator?
Recomendado para bombas acima de 1 CV, instalações trifásicas ou cabos longos.

---

##  9. Testes
- Testar continuidade com multímetro.
- Elevar/abaixar a boia e verificar mudança de estado.
- Ligar o sistema e observar funcionamento.

---

