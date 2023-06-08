# pythontamilfont
ReportLab, Pillow and python base Libary's TamilFont Render Problem Solved Code

This repository contains code that solves a render problem with Tamil fonts in python base Libary's. The problem is that Tamil fonts are not rendered correctly when they are used in a ReportLab document. This code fixes the problem by using a noto fonts rendering.
#example

To use this code, simply clone the repository and import the module into your project. Then, use the tam() function to render Tamil text in your document.

Usage

python
from tamfontpy import tamfont

text = "ரோஜா பூ அழகாக பூத்துள்ளது"

Render the Tamil text using the ReportLab Tamil font renderer.

rendered_text = tamfont(text)
text1 = rendered_text.tam()

Print the rendered text.

print(text1)

Code snippet

## Output

ரோஜா பூ அழகாக பூத்துள்ளது
