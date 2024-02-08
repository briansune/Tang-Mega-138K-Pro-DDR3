# TangMega-138KPro-DDR3

## EDA Version 19.9.01 !!!!!!

## This example is intended on TangMega 138KPro Modified DDR3 Board and Default Configuration Board

Aim: The example is continuously write and read back to check sanity of handshaking between DDR IP controller and custom FSM.

The debug methodology is address / 8 = write/read content app_data := {32{addr/8}}

# GAO Capture

![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/349fa9df-84fb-40d7-935f-b498e946cf5c)

# Explain of MT41J128M16-125:K and IP configuration

| | |
|-|-|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/0e2b1dda-d9fd-44b0-8206-f3e2cbf4225b)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/b33e9a66-1a5d-427e-8010-d9ee6422dcc5)|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/bbdd52a0-5ebf-462a-a72f-3e9bc41d0045)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/fbdd620e-df8d-405a-ba70-694802cac7ad)|

## DDR Datasheet

| | |
|-|-|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/88927293-569c-4da2-ad4b-125dba072a74)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/932aea6a-435d-4459-8a93-42abad7d26e8)|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/a53b2aba-ef5c-4fb3-bb95-4d9c552a6699)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/66ca86e7-ccb2-46b5-8a33-7f60fe29e0de)|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/a16acbcd-262d-4099-ab53-23a7132656d9)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/cb24ad39-118e-477f-833c-17b3449dcd71)|

# GAO Capture

![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/2da3f0b3-620e-48a2-b95d-d83e7d76b6fd)

# Explain of H5TQ4G63EFR-RDC and IP configuration

| | |
|-|-|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/3522899d-8af0-4a96-a506-6a87f33842d4)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/768fe3ff-3f0a-4a9d-a90a-9715c6b1e8fd)|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/985df7f0-86bf-42bd-82e1-11178538a8b6)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/6bfedaa1-c78e-4de2-a588-e522bb955745)|

## DDR Datasheet

Because the suffix of the DDR3 is RD and C with support of previous DDR speed.

| | |
|-|-|
|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/5b999d74-a5b7-4086-8ac1-49a6734d23d3)|![image](https://github.com/briansune/TangMega-138KPro-DDR3/assets/29487339/c3d7940c-33de-47cd-ba6e-01cab2827840)|

### For tCKE the datasheet does not clearly mention any data, from general rule of DDR3 mostly about 3N of tCK.
