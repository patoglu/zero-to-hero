<!-- @author ypatoglu -->

# Neural Networks: Zero to Hero

<!-- GORSEL BEKLENIYOR: docs/assets/hero.png kaydedilince alttaki satiri ac
![Neural network illüstrasyonu](assets/hero.png){ .hero }
-->

Andrej 10+ senedir neural network eğitiyor. Bu notebook'larla aşağıda dönüp biten ne varsa
anlayacağız.

Bu site, Andrej Karpathy'nin [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html)
serisini izlerken tuttuğum notlardan oluşuyor. Amacım videoyu özetlemek değil; anlatılan şeyi
gerçekten anladığımdan emin olmak, takıldığım yerleri ve kafama takılan soruları kayda geçirmek.

Serideki her video için ayrı bir Jupyter notebook var. Notlar Türkçe, kod ve teknik terimler
orijinal hâliyle bırakıldı — çünkü bu terimleri İngilizce hâlleriyle tanımak uzun vadede daha
işine yarıyor.

Soldaki menüden videolara ulaşabilirsiniz.

— **Yusuf Patoğlu**

## Videolar

| # | Video | Notlar | Durum |
|---|-------|--------|-------|
| 1 | [building micrograd](https://youtu.be/VMj-3S1tku0) | [notebook](notebooks/01-micrograd.ipynb) | devam ediyor |
| 2 | [building makemore](https://youtu.be/PaCmpygFfXo) | [notebook](notebooks/02-makemore.ipynb) | — |
| 3 | [makemore Part 2: MLP](https://youtu.be/TCH_1BHY58I) | [notebook](notebooks/03-makemore-mlp.ipynb) | — |
| 4 | [makemore Part 3: Activations & Gradients, BatchNorm](https://youtu.be/P6sfmUTpUmc) | [notebook](notebooks/04-makemore-bn.ipynb) | — |
| 5 | [makemore Part 4: Becoming a Backprop Ninja](https://youtu.be/q8SA3rM6ckI) | [notebook](notebooks/05-backprop-ninja.ipynb) | — |
| 6 | [makemore Part 5: Building a WaveNet](https://youtu.be/t3YJ5hKiMQ0) | [notebook](notebooks/06-wavenet.ipynb) | — |
| 7 | [Let's build GPT](https://www.youtube.com/watch?v=kCc8FmEb1nY) | [notebook](notebooks/07-gpt.ipynb) | — |
| 8 | [Let's build the GPT Tokenizer](https://youtu.be/zduSFxRajkE) | [notebook](notebooks/08-tokenizer.ipynb) | — |
| 9 | [Let's reproduce GPT-2 (124M)](https://youtu.be/l8pRSuU81PU) | [notebook](notebooks/09-reproduce-gpt2.ipynb) | — |

Tablodaki video adları YouTube'a, **notebook** bağlantıları ise notlarıma gider.

## Kaynak ve haklar

Serinin tamamı — videolar, anlatım ve orijinal kod — **Andrej Karpathy**'ye aittir.

- Videolar: [Andrej Karpathy / YouTube](https://www.youtube.com/@AndrejKarpathy)
- Kod: [karpathy/micrograd](https://github.com/karpathy/micrograd),
  [karpathy/makemore](https://github.com/karpathy/makemore),
  [karpathy/nanoGPT](https://github.com/karpathy/nanoGPT) — MIT lisanslı
- Seri ana sayfası: [karpathy.ai/zero-to-hero.html](https://karpathy.ai/zero-to-hero.html)
- Notlardaki neuron şeması: [cs231n.github.io](https://cs231n.github.io/neural-networks-1/) — MIT lisanslı, © Andrej Karpathy

Bu site resmî bir kaynak değildir, Karpathy ile bir bağlantısı yoktur ve videoların yerine geçmez.
Buradaki notlar yalnızca kendi öğrenme sürecimin kaydıdır; **hata içerebilir**. Bir çelişki
görürseniz orijinal videoyu esas alın.

Notebook'lardaki kodun büyük kısmı videolardaki koddur ve Karpathy'nin MIT lisanslı depolarından
gelir. Türkçe açıklamalar, yorumlar ve buradaki anlatım bana aittir ve
[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.tr) ile lisanslanmıştır:
kaynak göstererek paylaşabilirsiniz, ancak ticari olarak kullanamaz veya değiştirerek
yeniden yayımlayamazsınız.

Bir hata bulursanız ya da bir ekleme öneriniz varsa
[GitHub üzerinden](https://github.com/patoglu) bildirebilirsiniz.
