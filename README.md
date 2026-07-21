# Movie & Series Catalog App / Catalogo de Filmes e Series

> **Languages / Idiomas:** [Português](#português) | [English](#english)

---

<a name="português"></a>
## 🇧🇷 Português

### 📝 Descrição do Projeto
Este projeto é um aplicativo iOS desenvolvido em **SwiftUI** voltado para a exibição e navegação em um catálogo de filmes e séries de TV.

#### Principais Funcionalidades:
- **Catálogo de Mídias (`PrimeiraTela`):**
  - **Listagem de Filmes e Séries:** Apresenta listas verticais contendo título, ano de lançamento, bandeira do país de origem e a capa obtida via requisição remota assíncrona (`AsyncImage`).
  - **Carrossel de Recomendados:** Seção de rolagem horizontal (`ScrollView`) com capas de conteúdos recomendados.
  - **Componente Visual Personalizado (`StrokeText`):** Renderiza textos estilizados com contorno (stroke) customizável para títulos e seções.
  - **Design e Gradientes:** Interface estilizada utilizando gradientes lineares (`LinearGradient`) nas cores azul-petróleo (*teal*) para preto.
- **Tela de Detalhes (`SegundaTela`):**
  - Ao selecionar um item, o usuário é redirecionado para a tela de detalhes, onde são exibidos a capa em alta resolução com sombra projetada, categoria, ano, gênero, país e a nota do **IMDb** destacada.

---

### 🛠️ Tecnologias Utilizadas
- **Linguagem:** Swift
- **Framework:** SwiftUI (`NavigationStack`, `NavigationLink`, `AsyncImage`, `ScrollView`, `LinearGradient`)
- **IDE:** Xcode
- **Plataforma Target:** iOS / iPadOS

---

### 🚀 Como Executar o Projeto

#### Pré-requisitos
* Um computador Mac executando **macOS**.
* **Xcode 14** ou superior instalado.
* Conexão com a **internet** ativa (necessária para o carregamento das capas via `AsyncImage`).

#### Passo a Passo
1. **Clonar ou Baixar o Repositório:**
   ```bash
   git clone <URL_DO_REPOSITORIO>
   ```
2. **Abrir o Projeto no Xcode:**
   * Navegue até a pasta do projeto.
   * Dê um duplo clique no arquivo de projeto `.xcodeproj` (ex: `Desafio5 - 01-06.xcodeproj`).
3. **Verificar Assets / Ativos:**
   * Certifique-se de que o ativo de imagem local `tv` e a cor personalizada `amareloClaro` estejam presentes no catálogo `Assets.xcassets`.
4. **Executar no Simulador:**
   * Escolha o simulador desejado na barra superior do Xcode (ex: *iPhone 15*).
   * Pressione `Cmd + R` ou clique no botão **Play (▶)** para compilar e executar o aplicativo.

---

<a name="english"></a>
## 🇬🇧 English

### 📝 Project Description
This is an iOS application developed in **SwiftUI** designed for browsing and exploring a movie and TV series catalog.

#### Key Features:
- **Media Catalog (`PrimeiraTela`):**
  - **Movies & Series Lists:** Vertical lists displaying title, release year, country flag emoji, and poster artwork fetched asynchronously via remote URLs (`AsyncImage`).
  - **Recommended Carousel:** A horizontal scrolling section (`ScrollView`) featuring recommended titles.
  - **Custom Visual Component (`StrokeText`):** A custom view rendering outlined text with configurable stroke width and color for headings.
  - **Styling & Gradients:** Dynamic UI styled with full-screen linear gradients (`LinearGradient`) transitioning from teal to black.
- **Details View (`SegundaTela`):**
  - Tapping any media item navigates to a dedicated detail screen showing full-sized cover art with drop shadows, category, year, genre, country, and a highlighted **IMDb** score badge.

---

### 🛠️ Tech Stack
- **Language:** Swift
- **Framework:** SwiftUI (`NavigationStack`, `NavigationLink`, `AsyncImage`, `ScrollView`, `LinearGradient`)
- **IDE:** Xcode
- **Target Platform:** iOS / iPadOS

---

### 🚀 How to Run the Project

#### Prerequisites
* A Mac computer running **macOS**.
* **Xcode 14** or higher installed.
* Active **internet connection** (required for fetching poster images with `AsyncImage`).

#### Step-by-Step
1. **Clone or Download the Repository:**
   ```bash
   git clone <REPOSITORY_URL>
   ```
2. **Open the Project in Xcode:**
   * Navigate to the project directory.
   * Double-click the `.xcodeproj` file (e.g., `Desafio5 - 01-06.xcodeproj`).
3. **Verify Asset Catalog:**
   * Ensure that the `tv` image asset and the `amareloClaro` named color are present in `Assets.xcassets`.
4. **Run in Simulator:**
   * Select an iOS Simulator from the Xcode top bar (e.g., *iPhone 15*).
   * Press `Cmd + R` or click the **Play (▶)** button to build and launch the application.
