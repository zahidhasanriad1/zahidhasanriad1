<br/>

## 🧩 Core Profile

<table>
<tr>
<td width="33%" align="center" valign="top">

<h3>🔬 Research</h3>

<p>
  <img src="https://img.shields.io/badge/Object%20Detection-0F172A?style=for-the-badge&logo=opencv&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/3D%20Medical%20AI-0F172A?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Healthcare%20AI-0F172A?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Bengali%20NLP-0F172A?style=for-the-badge&logo=googletranslate&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Document%20Intelligence-0F172A?style=for-the-badge&logo=googledocs&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Vision%20Language%20Models-0F172A?style=for-the-badge&logo=openai&logoColor=white"/>
</p>

</td>
<td width="33%" align="center" valign="top">

<h3>⚙️ Engineering</h3>

<p>
  <img src="https://img.shields.io/badge/.NET%20Backend-1E3A8A?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/ASP.NET%20Core-1E3A8A?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/REST%20APIs-1E3A8A?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Financial%20ERP-1E3A8A?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Database%20Systems-1E3A8A?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Cloud%20Services-1E3A8A?style=for-the-badge&logo=googlecloud&logoColor=white"/>
</p>

</td>
<td width="33%" align="center" valign="top">

<h3>🚀 Building</h3>

<p>
  <img src="https://img.shields.io/badge/SkySeaLand%20Dataset-065F46?style=for-the-badge&logo=databricks&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/SkyDet%20Model-065F46?style=for-the-badge&logo=pytorch&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/AxonWrite-065F46?style=for-the-badge&logo=openai&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/AI%20APIs-065F46?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Research%20Tools-065F46?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/Cloud%20AI%20Systems-065F46?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

</td>
</tr>
</table>

<br/>

## 🔄 Work and Research Flow

```mermaid
%%{init: {
  "theme": "base",
  "themeVariables": {
    "background": "transparent",
    "primaryColor": "#0F172A",
    "primaryTextColor": "#FFFFFF",
    "primaryBorderColor": "#38BDF8",
    "lineColor": "#38BDF8",
    "secondaryColor": "#1E3A8A",
    "tertiaryColor": "#065F46",
    "fontFamily": "Inter, Segoe UI, Arial"
  }
}}%%

flowchart LR
    A["🔍 Research<br/>Problem"] --> B["📦 Dataset<br/>Design"]
    B --> C["🧠 Model<br/>Development"]
    C --> D["📊 Evaluation<br/>Benchmarking"]
    D --> E["🔎 Explainability<br/>Error Analysis"]
    E --> F["📄 Research<br/>Paper"]
    F --> G["🚀 AI System<br/>Deployment"]

    H["⚙️ Software<br/>Engineering"] --> I["🔗 Backend<br/>APIs"]
    I --> J["🗄️ Database<br/>Design"]
    J --> K["☁️ Cloud<br/>Services"]
    K --> G

    classDef research fill:#0F172A,stroke:#38BDF8,stroke-width:2px,color:#FFFFFF;
    classDef engineering fill:#1E3A8A,stroke:#93C5FD,stroke-width:2px,color:#FFFFFF;
    classDef output fill:#065F46,stroke:#5EEAD4,stroke-width:2px,color:#FFFFFF;

    class A,B,C,D,E,F research;
    class H,I,J,K engineering;
    class G output;
