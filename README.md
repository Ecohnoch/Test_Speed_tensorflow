# Test_Speed_tensorflow

Author: Ecohnoch (Chuyuan Xiong)

Test the different methods to load data from VoxCeleb1.


Feed_dict:

```
Counter: 0 Step time: 6.295599699020386 Batch time: 2.5750744342803955
Counter: 1 Step time: 7.346299886703491 Batch time: 0.4196662902832031
Counter: 2 Step time: 7.89916205406189 Batch time: 0.42375802993774414
Counter: 3 Step time: 7.849005222320557 Batch time: 0.42288804054260254
Counter: 4 Step time: 7.825454950332642 Batch time: 0.42127156257629395
Counter: 5 Step time: 7.741421699523926 Batch time: 0.42023229598999023
Counter: 6 Step time: 7.170980215072632 Batch time: 0.3953855037689209
Counter: 7 Step time: 7.0572052001953125 Batch time: 0.39606690406799316
Counter: 8 Step time: 7.011394262313843 Batch time: 0.4239654541015625
Counter: 9 Step time: 7.550851821899414 Batch time: 0.41985249519348145
10 Batch time consumed:  73.74794006347656
```


Multi_thread(Queue Buffer=3):

```
Counter: 0 Step time: 6.949103832244873 Batch time: 6.949103832244873
Counter: 1 Step time: 0.4178884029388428 Batch time: 0.41788816452026367
Counter: 2 Step time: 0.41602659225463867 Batch time: 0.41602659225463867
Counter: 3 Step time: 1.6344246864318848 Batch time: 1.6344244480133057
Counter: 4 Step time: 0.4172630310058594 Batch time: 0.4172627925872803
Counter: 5 Step time: 0.4188086986541748 Batch time: 0.4188082218170166
Counter: 6 Step time: 3.5055649280548096 Batch time: 3.5055646896362305
Counter: 7 Step time: 0.41728734970092773 Batch time: 0.41728711128234863
Counter: 8 Step time: 0.4174153804779053 Batch time: 0.41741514205932617
Counter: 9 Step time: 3.524942398071289 Batch time: 3.52494215965271
10 Batch time consumed:  18.121190071105957
```

TF_Records:

```
Counter: 0 Step time: 6.16588568687439 Batch time: 2.5156548023223877
Counter: 1 Step time: 0.4680795669555664 Batch time: 0.4195573329925537
Counter: 2 Step time: 0.4180431365966797 Batch time: 0.3949098587036133
Counter: 3 Step time: 0.4179658889770508 Batch time: 0.3945798873901367
Counter: 4 Step time: 0.417874813079834 Batch time: 0.39447832107543945
Counter: 5 Step time: 0.4183065891265869 Batch time: 0.39487552642822266
Counter: 6 Step time: 0.4181385040283203 Batch time: 0.3947765827178955
Counter: 7 Step time: 0.4182932376861572 Batch time: 0.39474034309387207
Counter: 8 Step time: 0.44022130966186523 Batch time: 0.3950035572052002
Counter: 9 Step time: 0.4184234142303467 Batch time: 0.3947596549987793
10 Batch time consumed:  10.002059936523438
```


References:

```
@InProceedings{Xie19,
  author       = "W. Xie, A. Nagrani, J. S. Chung, A. Zisserman ",
  title        = "Utterance-level Aggregation For Speaker Recognition In The Wild.",
  booktitle    = "ICASSP, 2019",
  year         = "2019",
}

@InProceedings{Chung18,
  author       = "J. S. Chung*, A. Nagrani*, A. Zisserman ",
  title        = "VoxCeleb2: Deep Speaker Recognition.",
  booktitle    = "INTERSPEECH, 2018",
  year         = "2018",
}

@InProceedings{Nagrani17,
  author       = "A. Nagrani*, J. S. Chung*, A. Zisserman ",
  title        = "VoxCeleb: A Large-scale Speaker Identification Dataset.",
  booktitle    = "INTERSPEECH, 2017",
  year         = "2018",
}
```