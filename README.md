# Engine — UE Master Bridge

Pacotes para Unreal Engine 5.8 (Win64):

- [Baixar plugin UE Master Bridge 0.10.0 — correção de malhas da fase 5](https://github.com/flepy20221-spec/engine/raw/refs/heads/main/UE_Master_Bridge_UE58_Acoes_v0.10.0_malhas.zip)
- [Baixar UEMasterController 0.10.0](https://github.com/flepy20221-spec/engine/raw/refs/heads/main/UEMasterController_Acoes_v0.10.0.zip)

O pacote do plugin contém o código fonte, o arquivo `LEIA-ME.md` e os scripts de teste. Compile e instale no Windows com UE 5.8; feche o Editor antes da instalação e reinicie-o em seguida. Para descobrir malhas presentes no projeto, execute `python testar_personagens.py --list-meshes --search Manny` e escolha o caminho exibido. Depois execute `python testar_personagens.py --write --mesh /Game/Caminho/MalhaExistente` em um projeto de teste.

A correção de malhas ainda precisa ser compilada e validada no Editor 5.8; o status do protocolo continua em `bridge_version: 0.10.0` para compatibilidade com o Controller. O pacote [0.10.0 original](https://github.com/flepy20221-spec/engine/raw/refs/heads/main/UE_Master_Bridge_UE58_Acoes_v0.10.0.zip) permanece disponível para referência.
