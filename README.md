# Blender Add-on: Sort Shapekeys
FaceCap用にBlender上でシェイプキーを並べ替えるスクリプトです。[DLはこちら](https://github.com/3str6/sort_shapekeys/releases/download/v1.0/sort_shapekeys.zip)    
<br>
![アドオン画像](./doc/sort_shapekeys_00.jpg)

## 機能一覧_Functions  
### Type  
FaceCap/iFacialMocapを選択します。  
以降のCheck, Create Missings, Sortはここで選択したTypeに従って処理します。  

### Check  
選択しているオブジェクトにTypeのシェイプキーがすべて存在するかをチェックします。  
存在しなかったシェイプキー名をinfoに表示します。  

### Create Missings  
選択しているオブジェクトにTypeのシェイプキーがすべて存在するかをチェックし、  
存在しなかったシェイプキーを空シェイプキーとして作成します。  

### Sort  
選択しているオブジェクトのシェイプキーをTypeに従ってsortします。  
Typeのシェイプキー52個すべてが揃っていない場合、この操作はキャンセルされます。  

## Shapekeyのsort順  
### FaceCap  
0：Basis  
1：browInnerUp  
2：browDown_L  
3：browDown_R  
4：browOuterUp_L  
5：browOuterUp_R  
6：eyeLookUp_L  
7：eyeLookUp_R  
8：eyeLookDown_L  
9：eyeLookDown_R  
10：eyeLookIn_L  
11：eyeLookIn_R  
12：eyeLookOut_L  
13：eyeLookOut_R  
14：eyeBlink_L  
15：eyeBlink_R  
16：eyeSquint_L  
17：eyeSquint_R  
18：eyeWide_L  
19：eyeWide_R  
20：cheekPuff  
21：cheekSquint_L  
22：cheekSquint_R  
23：noseSneer_L  
24：noseSneer_R  
25：jawOpen  
26：jawForward  
27：jawLeft  
28：jawRight  
29：mouthFunnel  
30：mouthPucker  
31：mouthLeft  
32：mouthRight  
33：mouthRollUpper  
34：mouthRollLower  
35：mouthShrugUpper  
36：mouthShrugLower  
37：mouthClose  
38：mouthSmile_L  
39：mouthSmile_R  
40：mouthFrown_L  
41：mouthFrown_R  
42：mouthDimple_L  
43：mouthDimple_R  
44：mouthUpperUp_L  
45：mouthUpperUp_R  
46：mouthLowerDown_L  
47：mouthLowerDown_R  
48：mouthPress_L  
49：mouthPress_R  
50：mouthStretch_L  
51：mouthStretch_R  
52：tongueOut  
### iFacialMocap
0：Basis  
1：browInnerUp  
2：browDownLeft  
3：browDownRight  
4：browOuterUpLeft  
5：browOuterUpRight  
6：eyeLookUpLeft  
7：eyeLookUpRight  
8：eyeLookDownLeft  
9：eyeLookDownRight  
10：eyeLookInLeft  
11：eyeLookInRight  
12：eyeLookOutLeft  
13：eyeLookOutRight  
14：eyeBlinkLeft  
15：eyeBlinkRight  
16：eyeSquintLeft  
17：eyeSquintRight  
18：eyeWideLeft  
19：eyeWideRight  
20：cheekPuff  
21：cheekSquintLeft  
22：cheekSquintRight  
23：noseSneerLeft  
24：noseSneerRight  
25：jawOpen  
26：jawForward  
27：jawLeft  
28：jawRight  
29：mouthFunnel  
30：mouthPucker  
31：mouthLeft  
32：mouthRight  
33：mouthRollUpper  
34：mouthRollLower  
35：mouthShrugUpper  
36：mouthShrugLower  
37：mouthClose  
38：mouthSmileLeft  
39：mouthSmileRight  
40：mouthFrownLeft  
41：mouthFrownRight  
42：mouthDimpleLeft  
43：mouthDimpleRight  
44：mouthUpperUpLeft  
45：mouthUpperUpRight  
46：mouthLowerDownLeft  
47：mouthLowerDownRight  
48：mouthPressLeft  
49：mouthPressRight  
50：mouthStretchLeft  
51：mouthStretchRight  
52：tongueOut  
