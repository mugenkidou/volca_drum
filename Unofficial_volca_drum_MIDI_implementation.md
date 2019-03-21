# Unofficial MIDI implementation for volca drum

Feburary 25th, 2019

------

This contents of this publication has no relations with KORG inc. Please do not send any inquiries to KORG inc. Should you have any questions, please send them to myself, Mugenkidou([mugenkidou.wakakusa@gmail.com](mailto:mugenkidou.wakakusa@gmail.com))
When operating MIDI devices according to this publication's contents, please make sure to make any necessary  backups and proceed at your own risk. We will not take any responsibility for any data loss, hardware failure, or other damage.

------
# Control Change

## Layer 1

|Control No.|value|Parameter name|
|---:|---|---|
| 7 (0x07)|0-127|LEVEL|
|26 (0x1A)|0-127|MOD AMOUNT(64:CENTER)|
|27 (0x1B)|0-127|MOD RATE|
|23 (0x17)|0-127|PITCH|
|17 (0x11)|0-127|EG ATTACK|
|18 (0x12)|0-127|EG RELEASE|
|14 (0x0E)|0-127|SELECT|


## Layer 2

|Control No.|value|Parameter name|
|---:|---|---|
| 8 (0x08)|0-127|LEVEL|
|28 (0x1C)|0-127|MOD AMOUNT(64:CENTER)|
|29 (0x1D)|0-127|MOD RATE|
|24 (0x18)|0-127|PITCH|
|19 (0x13)|0-127|EG ATTACK|
|20 (0x14)|0-127|EG RELEASE|
|15 (0x0F)|0-127|SELECT|


## Layer 1-2

|Control No.|value|Parameter name|
|---:|---|---|
|9 (0x09)|0-127|LEVEL|
|30 (0x1E)|0-127|MOD AMOUNT(64:CENTER)|
|31 (0x1F)|0-127|MOD RATE|
|25 (0x19)|0-127|PITCH|
|21 (0x15)|0-127|EG ATTACK|
|22 (0x16)|0-127|EG RELEASE|
|16 (0x10)|0-127|SELECT|


## Common

|Control No.|value|Parameter name|
|---:|---|---|
|48 (0x30)|0-127|BIT|
|49 (0x31)|0-127|FLD|
|50 (0x32)|0-127|DRV|
|10 (0x0A)|0-127|PAN(64:CENTER)|
|51 (0x33)|0-127|GAN|
|12 (0x0C)|0-127|SEND|


## WAVE GUIDE
|Control No.|value|Parameter name|
|---:|---|---|
|117 (0x75)|0-127|DECAY|
|118 (0x76)|0-127|BODY|
|119 (0x77)|0-127|TUNE|
 

## SYSTEM
|Control No.|value|Parameter name|
|---:|---|---|
|3  (0x03)|0-15|LOAD KIT|


