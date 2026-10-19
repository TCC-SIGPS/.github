# SIGPS: Sistema Inteligente de Gestão e Priorização em Saúde

Bem-vindo à organização **TCC-SIGPS**. Este espaço reúne os repositórios que compõem o **SIGPS**, uma solução desenvolvida para apoiar a gestão e a priorização de atendimentos em saúde por meio de uma arquitetura modular, integrando interface web, serviços de backend e modelos de aprendizado de máquina.

O objetivo central do SIGPS é oferecer suporte à tomada de decisão e à organização de fluxos em saúde, combinando usabilidade, regras de negócio bem definidas e inteligência analítica.

---

## Repositórios

| Repositório | Descrição | Tecnologias principais (exemplos) |
| :--- | :--- | :--- |
| [**SIGPS-Frontend**](https://github.com/TCC-SIGPS/SIGPS-Frontend) | Interface web do sistema. Responsável pela construção da UI, visualização de dados e integração com a API, oferecendo suporte à gestão e à priorização em saúde. | A definir (ex.: React, Vue, Angular) |
| [**SIGPS-Backend**](https://github.com/TCC-SIGPS/SIGPS-Backend) | API e serviços responsáveis pelas regras de negócio, persistência de dados e disponibilização dos serviços que suportam a interface web e os fluxos de gestão e priorização. | A definir (ex.: Node.js, Python/Django, Java/Spring) |
| [**SIGPS-Machine-Learning**](https://github.com/TCC-SIGPS/SIGPS-Machine-Learning) | Módulo de inteligência analítica. Responsável pelo desenvolvimento, treinamento e disponibilização de modelos de aprendizado de máquina para apoio à priorização e triagem em saúde. | Python, scikit-learn, TensorFlow/PyTorch |

> **Nota:** As tecnologias principais são exemplos e devem ser substituídas pelas stacks efetivamente utilizadas em cada repositório.

---

## Arquitetura em alto nível

O SIGPS foi concebido para operar de forma integrada:

1.  **Frontend** consome os serviços expostos pelo **Backend**.
2.  **Backend** centraliza as regras de negócio, a segurança e a persistência, além de orquestrar chamadas ao módulo de **Machine Learning** quando necessário.
3.  **Machine Learning** fornece suporte analítico para priorização, classificação ou triagem, conforme os requisitos do sistema.

Essa separação favorece a manutenção, a evolução independente de cada componente e a clareza sobre as responsabilidades de cada parte da solução.

---

## Como contribuir

Cada repositório possui seu próprio `README.md` com instruções específicas de instalação, configuração e execução. Recomenda-se consultar o repositório correspondente antes de abrir issues ou enviar pull requests.

Para dúvidas gerais sobre a organização ou o projeto como um todo, utilize a aba **Discussions** (se habilitada) ou entre em contato com os mantenedores.

---

## Licença

O projeto é disponibilizado para fins acadêmicos e de pesquisa. Consulte o arquivo `LICENSE` em cada repositório para obter os termos exatos de uso e distribuição.

---

**SIGPS**: Sistema Inteligente de Gestão e Priorização em Saúde.
