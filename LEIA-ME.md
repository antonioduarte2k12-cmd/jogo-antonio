# Yellow Cab: Manhattan Rush

Jogo arcade 3D de entregas pelas ruas de Nova York, feito com Three.js e sem dependências npm.

## Abrir com Node portátil

1. Extraia o Node.js portátil para uma pasta.
2. Abra o terminal nessa pasta do jogo.
3. Execute o servidor com o caminho do `node.exe` portátil:

```powershell
..\node-portable\node.exe .\server.mjs
```

4. Abra `http://127.0.0.1:4173` no navegador.

O navegador precisa de internet para carregar o módulo Three.js e as fontes. Para usar outra porta, defina a variável `PORT` antes de iniciar o servidor.

## Controles

- `W` / seta para cima: acelerar
- `S` / seta para baixo: frear ou dar ré
- `A` / seta para esquerda e `D` / seta para direita: virar
- `Espaço`: freio de mão
- Celular/tablet: controles direcionais na tela

Entregue os oito pacotes antes do cronômetro zerar.