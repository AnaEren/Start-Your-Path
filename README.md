# Start-Your-Path
Operações em um banco de dados não relacional com uma simulação de inserção de informações por bots


## 1. SOBRE A APLICAÇÃO

### 1.1. PROPOSTA 
A proposta desta aplicação é centralizar e organizar oportunidades de emprego e estágio de diversas fontes em uma única plataforma, já que hoje existem inúmeras plataformas e sites com informações dispersas, dificultando para usuários a busca por empregos.

### 1.2. UTILIDADE
A aplicação oferece um banco de dados constantemente atualizado que integra ofertas de várias plataformas, coletada por bots. Ela também permite que empresas publiquem diretamente suas vagas, ampliando o alcance das oportunidades.


## 2.  SOLUÇÃO COM BANCO DE DADOS

### 1.2. JSON FINAL
Da collection Jobs:

    {
    
        "Job Title": "Chemical Engineer",
	
        
	"Job Description": "Monitor and maintain product quality standards, perform inspections, and implement quality control procedures.",
        
	"Role": "Quality Control Engineer",
        
	"Company": "COM100053",
        
	"Contact": "886.347.2730x938",
        
	"Contact Person": "Jessica Fox",
        
	"Work Type": "Intern",
        
	"Job Portal": "Idealist",
        
	"Qualifications": "BCA",
        
	"Location": [
        
	    48.669,
            
	    19.699
        
	],
        
	"Country": "Slovak Republic",
        
	"Job Posting Date": "2021-10-12",
        
	"Salary": {
        
	    "min": 64000,
            
	    "max": 104000
        
	},
        
	"Experience": {
        
	    "min": 3,
          
	    "max": 8
  
	}

    },

Da collection Companies:
    
    {
    
	"_id": "COM100004",
        
	"Company": "Cairn Energy",
        
	"Company Profile": {
        
	    "Sector": "Energy",
            
	    "Industry": "Energy - Oil & Gas Exploration & Production",
            
	    "City": "Edinburgh",
            
	    "State": "Scotland",
            
	    "Zip": "EH2 4NH",
            
	    "Website": "https://www.cairnenergy.com/",
            
	    "Ticker": "CNE",
            
	    "CEO": "Simon Thomson"
        },
	
	"Company Size": 53944
   
    },

### 2.3. SIMULAÇÃO DE INJEÇÃO DE DADOS
Fiz uma simulação de um bot injetando dados no banco de dados, usando o python e um arquivo JSON; o código da simulação pode ser conferido da seção da aplicação.
	

## REFERÊNCIAS
Documentação do MongoDB, Disponível em: https://www.mongodb.com/docs/

