# NTSL Profit VS Code Extension

Syntax highlighting para arquivos NTSL do Profit da Nelógica (.src).

## Instalação

1. Instale o `vsce`:
   ```bash
   npm install -g @vscode/vsce
   ```

2. Gere o pacote:
   ```bash
   cd vscode-ntsl-extension
   vsce package
   ```

3. Instale via VS Code:
   - `Extensions: Install from VSIX...`

## Recursos

- Keywords: input, var, function, procedure, begin, end, if, then, else, for, to, downto, do, while, repeat, until
- Tipos: Float, Real, Integer, Boolean, String, Serie
- Booleanos: Verdadeiro, Falso, True, False
- 400+ funções do Manual NTSL
- Variáveis de série: Open, High, Low, Close, Volume, Date, Time, CurrentBar...
- Constantes de cor: clGreen, clRed, clBlue...
- Comentários: //, { }, (* *)

## Fonte

Manual NTSL v4.7
