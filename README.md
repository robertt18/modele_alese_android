## Descriere
Acest repository conține modelele finale selectate convertite în 
format LiteRT (.tflite) pentru deployment pe dispozitive Android, 
precum și notebook-ul de conversie utilizat.

## Modele finale selectate
| Model | Bază de date | Acuratețe | Dimensiune .tflite |
|---|---|---|---|
| MobileNet | FER-2013 augmented | 80.94% | ~3.6 MB |
| V-CNN | CK+ | 90.54% | ~1.6 MB |
| V-CNN | FER-2013 original | 59.96% | ~1.6 MB |
| VRES-CNN | RAF-DB | 76.08% | ~0.4 MB |

## Conținut
- `mobilenet_gpu_fer-2013-augmented.tflite`
- `vcnn_gpu_ck.tflite`
- `vcnn_gpu_fer-2013-original.tflite`
- `vrescnn_gpu_raf_db.tflite`
- `conversie_android_tflite.ipynb`
