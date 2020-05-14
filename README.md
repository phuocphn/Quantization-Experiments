# Quantization-Experiments

**DSQ** https://github.com/ricky40403/DSQ
<pre>
python train.py -a resnet18  -q DSQ --quan_bit 4 --quantize_input .../imagenet/
</pre>
After training 90 epochs, (2 days 17 hours) I got Acc@1 69.544 Acc@5 89.104

Server: Uranus, 4 GPU TITAN Xp.

