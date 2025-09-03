Plataforma de Exercícios de Memória com SAM 2
Sobre o Projeto

Este projeto foi desenvolvido na cadeira de Criatividade Computacional por:

Vinícius Macêdo
Ivo Neto
Walter Crasto
Francisco
Niltton Szpak

A plataforma tem como objetivo oferecer exercícios de memória voltados principalmente para idosos, de forma simples e interativa.

Como Funciona

O sistema utiliza o modelo Segment Anything 2 (SAM 2), da Meta, para segmentar imagens automaticamente,
após a segmentação, o usuário associa uma frase/descrição a cada segmento da imagem. Mais tarde, no exercício de memória, o usuário recebe apenas o segmento da imagem (sem a descrição original), e deve escrever novamente a descrição que lembra.O sistema compara a nova descrição com a original e informa se estão semelhantes, promovendo treino cognitivo e memorização.

Motivação

O projeto foi pensado principalmente para estimular a memória de idosos, ajudando a exercitar recordações visuais e linguísticas de forma lúdica e acessível.

Tecnologias

SAM 2 (Meta) – Segmentação de imagens
Gradio – Interface interativa
FuzzyWuzzy – Comparação de similaridade entre descrições
