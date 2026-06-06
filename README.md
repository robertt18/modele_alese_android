## Descriere
Acest repository conține modelele finale selectate convertite în 
format LiteRT (.tflite) pentru deployment pe dispozitive Android, 
precum și notebook-ul de conversie utilizat.

## Structură
├──in keras
|   ├── mobilenet_gpu_fer-2013-augmented
|   ├── vcnn_gpu_ck+
|   ├── vcnn_gpu_fer-2013-original
|   └── vrescnn_gpu_raf-db
└──notebook pt conversie in android + modelul .tflite salvat
    ├──CK+
    |   ├── notebook conversie model CK+
    |   └── model .tflite
    ├──fer original
    |   ├── notebook conversie model fer_original
    |   └── model .tflite
    ├──fer_augmented
    |   ├── notebook conversie model fer_augmented
    |   └── model .tflite
    └──RAF-DB
        ├── notebook conversie model RAF-DB
        └── model .tflite
        
## Modele finale selectate
| Model | Bază de date | Acuratețe | 
|---|---|---|
| MobileNet | FER-2013 augmented | 80.91% |
| V-CNN | CK+ | 90.54% |
| V-CNN | FER-2013 original | 59.96% |
| VRES-CNN | RAF-DB | 76.08% | 


