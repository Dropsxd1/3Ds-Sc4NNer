# 3Ds-Sc4NNer — Sprint 0

## Objetivo

Preparar o ambiente de desenvolvimento e validar o funcionamento das ferramentas necessárias para a reconstrução tridimensional.

## Ambiente configurado

- Sistema operacional: Ubuntu 26.04.1 LTS (WSL2)
- GPU: NVIDIA GeForce GTX 1650 (4 GB)
- CUDA Toolkit: 13.4
- GCC: 15.2.0
- COLMAP: 4.3.0.dev0 com CUDA
- Controle de versão: Git e GitHub

## Atividades concluídas

- [x] Instalação e configuração do WSL2
- [x] Configuração do Ubuntu
- [x] Configuração do Git e GitHub
- [x] Instalação e teste do CUDA Toolkit
- [x] Reconhecimento da GTX 1650
- [x] Compilação do COLMAP com CUDA
- [x] Instalação e validação do COLMAP
- [x] Primeiro teste de extração de características SIFT

## Problema encontrado

Durante o primeiro experimento com seis imagens, o COLMAP apresentou o erro:

`CAMERA_SINGLE_DIM_ERROR`

O problema ocorreu porque as fotografias possuíam resoluções diferentes.

Também identificamos arquivos com extensão JPG, mas conteúdo PNG, além da baixa resolução das imagens.

## Solução planejada

Realizar uma nova captura de aproximadamente 16 fotografias utilizando a webcam Logitech C920, mantendo:

- Resolução padronizada de 1280 × 720
- Iluminação constante
- Fundo de cor sólida
- Câmera fixa
- Objeto rotacionado entre as capturas

## Próximas atividades

- [ ] Preparar novas imagens
- [ ] Executar extração SIFT
- [ ] Executar correspondência entre imagens
- [ ] Gerar reconstrução esparsa
- [ ] Validar nuvem de pontos
- [ ] Executar reconstrução densa
- [ ] Criar malha 3D
- [ ] Exportar modelo em GLB

## Situação atual

O ambiente de processamento está preparado. A próxima etapa será validar a reconstrução tridimensional utilizando fotografias reais de um objeto.
