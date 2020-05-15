# Quantization-Experiments

**DSQ** https://github.com/ricky40403/DSQ
<pre>
python train.py -a resnet18  -q DSQ --quan_bit 4 --quantize_input .../imagenet/
</pre>
After training 90 epochs, (2 days 17 hours) I got Acc@1 69.544 Acc@5 89.104

Server: Uranus, 4 GPU TITAN Xp.

![GitHub Logo](/dsq_quantize_input.png)

<pre>
python train.py -a resnet18  -q DSQ --quan_bit 4  .../imagenet/
</pre>
After training 90 epochs, (2 days 5 hours) I got Acc@1 69.85

Server: Europa, 4 GPU GeForce GTX 1080

![GitHub Logo](/dsq_no_quantize_input.png)
