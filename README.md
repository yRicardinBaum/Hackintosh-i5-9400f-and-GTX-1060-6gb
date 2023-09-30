# Hackintosh MacOS Ventura 13.5 - Intel Coffe Lake + GPU Nvidia 

### Main Specs:
	* Gigabyte B360M DS3H
	* Intel core i5-9400f Coffee-Lake
	* GALAX GTX 1060 6GB (GDDR5X / GP104)
	* 16GB DDR4 2666mhz
	* Realtek 8118 Gaming 

**Observação:**
1. Se você usar o mesmo processador que o meu _(ou parecido)_ e GPU, você pode apenas copiar e colar a pasta `EFI` dentro da sua partição.
2. Para ativação da placa de video foi usado o aplicativo [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher).
3. Foi usado o aplicativo [SSDTTime](https://github.com/corpnewt/SSDTTime) para criação das ACPIs necessárias para o bom uso do MacOS.

**AVISO IMPORTANTE:**

**Algumas GPUs acima da série Kepler não possui suporte da própria NVIDIA**, ou como são chamados, WebDrivers. Por isso foi feito uma 'gambiarra' que vem sendo muito usada por pessoas que possuem placas de video não suportadas, e por isso podem apresentar problemas como glitches e etc, porém com a minha vivência atual com o sistema, esses poucos glitches não me afetaram em absolutamente nada. Porém, se você planeja utilizar a acelaração de hardware ou a API Metal, usar essa EFI não vai suprir as suas necessidades, **já que a GPU, por não ser suportada nativamente, não possui esse tipo de tecnologia.** Entretanto se você deseja usar para uso básico, como programação e estudos, usar essa EFI pode é uma boa opção.



## Ativar a GPU
Após terminar a instalação do MacOS e estar bootando sem o pendrive, você perceberá uma lentidão extrema nas animações e na fluidez do sistema, isso porque você ainda não ativou a GPU, para fazer isso instale o OpenCore Legacy Patcher [OpenCore Legacy Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher), e então assista ao [tutorial de ativação](https://www.youtube.com/watch?v=miWgnT2KOjY)

## Dicas extras 
Após total finalização da instalação, eu super recomendo você dar uma olhada nesse repositório para terminar de configurar o seu macos acessando [esse link](https://dortania.github.io/OpenCore-Post-Install/#how-to-follow-this-guide).

## Resultado final
**O que realmente funciona?**: 
> Tudo, apenas com as limitações da GPU ditas nos tópicos anteriores.


## Imagens
![Informações](https://i.imgur.com/7BMutwx.png)
![Aceleração de Hardware](https://i.imgur.com/ReDUduk.png)