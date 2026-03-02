# Engine de Tradução e Mapeamento de Termos Técnicos
# Desenvolvido por Vitor - Estudante de ADS (Foco em Compliance)

# O dicionário é a base de conhecimento do sistema
termos_tecnicos = {
    "compliance": "conformidade",
    "risk_assessment": "análise de risco",
    "data_privacy": "privacidade de dados"
}

def traduzir_termo(termo):
    # Uso do .get() para evitar que o sistema quebre (Maturidade Técnica)
    resultado = termos_tecnicos.get(termo.lower(), "Termo não encontrado na base de dados.")
    return resultado

# Simulação de consulta
termo_busca = "compliance"
print(f"Resultado da análise: {traduzir_termo(termo_busca)}")
