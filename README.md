# Avalia-o-1-CITAV-
Corrigir erros de Sintaxe e de Semantica. 

### Relatório de Correções de Erros

Após análise linha por linha dos arquivos enviados pelo formador, os seguintes erros de sintaxe e semântica foram identificados e corrigidos:

 
1. **Erro de sintaxe**: Tag `<p>` não fechada no primeiro cartão da seção "Sobre" (linha ~70).  
   - **Correção**: Adicionado `</p>` antes de `</div>`.

2. **Erro semântico**: Uso inconsistente de `<h4>` em vez de `<h3>` no terceiro cartão da seção "Sobre" (linha ~85), quebrando a hierarquia de cabeçalhos.  
   - **Correção**: Alterado para `<h3>` para manter consistência.

3. **Erro semântico**: Campo de entrada de email com `type="text"` em vez de `type="email"` na seção Newsletter (linha ~270), reduzindo validação e acessibilidade.  
   - **Correção**: Alterado para `type="email"`.

4. **Erro de sintaxe**: Tag `<a>` não fechada no link "Sobre a F1" no footer (linha ~290).  
   - **Correção**: Adicionado `</a>` antes de `</li>`.

#### style_erros.css
- Nenhum erro encontrado. O CSS estava bem formado e consistente com as correções no HTML.

**Validação final**: Após as correções, ambos os arquivos passaram na verificação sem erros. O código agora está sintaticamente correto e semanticamente apropriado para HTML5 e CSS3.