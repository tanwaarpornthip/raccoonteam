# บทที่ 2 ตลาดการเงินและเครื่องมือการลงทุน

บทความนี้แปลและดัดแปลงมาจากบทความของ Binance Academy เรื่อง ["A complete guide to cryptocurrency for beginners"](https://academy.binance.com/en/articles/a-complete-guide-to-cryptocurrency-trading-for-beginners?ref=JLI1VBLA&utm_source=BinanceTwitter&utm_medium=GlobalSocial&utm_campaign=GlobalSocial) เมื่อวันที่ 4 ตุลาคม 2020

![](../.gitbook/assets/image%20%281%29.png)

### เนื้อหา

* [เครื่องมือทางการเงิน \(Financial instrument\) คืออะไร](beginner-chapter-2.md#financial-instrument)
* [spot market](beginner-chapter-2.md#spot-market)
* [การเทรดบน Margin](beginner-chapter-2.md#margin)
* [ตลาดอนุพันธ์ \(Derivatives market\)](beginner-chapter-2.md#derivatives-market)
* [Forward และ futures contracts](beginner-chapter-2.md#forward-futures-contracts)
* [Perpetual futures contracts](beginner-chapter-2.md#perpetual-futures-contracts)
* [options contracts](beginner-chapter-2.md#what-are-options-contract)
* [ตลาดแลกเปลี่ยนเงินตราต่างประเทศ \(Forex\)](beginner-chapter-2.md#forex)
* [Leveraged tokens](beginner-chapter-2.md#leveraged-tokens)

### เครื่องมือทางการเงิน \(Financial instrument\) คืออะไร

เครื่องมือทางการเงิน \(Financial instrument\) คือทรัพย์สินใด ๆ ก็ตามที่สามารถนำมาแลกเปลี่ยนซื้อขายได้ เช่น เงินสด โลหะ \(ทองคำ เงิน\) หนังสือหลักฐานเอกสารแสดงความเป็นเจ้าของต่าง ๆ \(เช่น โฉนดที่ดิน\) สิทธิในการได้รับผลประโยชน์จากกรมธรรม์ต่าง ๆ ซึ่งเครื่องมือทางการเงินอาจฟังดูซับซ้อน แต่ไอเดียหลัก ๆ คือการที่ผู้ใช้สามารถที่จะทำการซื้อขายแลกเปลี่ยนทรัพย์สินที่เครื่องมือเหล่านี้เป็นตัวกำหนดมูลค่าได้

การจำแนกประเภทของเครื่องมือทางการเงิน สามารถทำได้หลายรูปแบบ หนึ่งในรูปแบบที่นิยมคือจำแนกเป็นเครื่องมือประเภทเงินสด กับเครื่องมือประเภทอนุพันธ์ โดยเครื่องมืออนุพันธ์จะมีการประเมินมูลค่าโดยอิงมูลค่าของสิ่งอื่น ๆ \(เช่น คริปโต\) นอกจากนั้นแล้วยังสามารถจำแนกเป็นเครื่องมือประเภทตราสารทุนหรือตราสารหนี้ได้อีกด้วย

แล้วคริปโตสมควรจะถูกจำแนกอยู่ในประเภทใด... เนื่องจากคริปโตเป็นเทคโนโลยีที่ใหม่ จึงสามารถเข้าได้กับหลาย ๆ ประเภท วิธีจำแนกที่ง่ายที่สุดคือการเรียกคริปโตว่าสินทรัพย์ดิจิทัล แต่อย่างไรก็ตาม คริปโตมีศักยภาพที่จะเปลี่ยนโครงสร้างและสร้างสถาปัตยกรรมใหม่ให้กับโลกทางการเงินและเศรษฐกิจที่เรารู้จักอยู่ได้

ดังนั้นแล้ว คริปโตจึงถูกจัดอยู่ในประเภทใหม่ที่เรียกว่าสินทรัพย์ดิจิทัล นอกจากนั้นยังมีประเภทการจำแนกใหม่ ๆ ที่เกิดขึ้นในโลกคริปโทที่ไม่สามารถหาคู่เทียบได้ในปัจจุบัน เช่น Decentralized Finance \(DeFi\)

### Spot market

Spot market คือ ตลาดที่ใช้ในการแลกเปลี่ยนเครื่องมือทางการเงินในรูปแบบของการซื้อขายและส่งมอบทันที คำว่าส่งมอบในที่นี้ หมายถึงการแลกเปลี่ยนสินทรัพย์กับเงินสดในทันที ซึ่งการใช้เงินสดในตลาด Spot ต่างกับตลาดประเภทอื่นที่อาจจะไม่ได้แลกเปลี่ยนกันด้วยเงินสด เช่น ตลาด Futures ที่สามารถมีการแลกเปลี่ยนสินทรัพย์ต่าง ๆ ในภายหลัง และไม่ต้องใช้เงินสดก็ได้

เนื่องจากการซื้อขายและส่งมอบแบบทันทีใน spot market ราคาของสินทรัพย์ต่าง ๆ ที่อยู่ในตลาดดังกล่าวจะเรียกว่า spot price

ในโลกคริปโท เช่น ตลาด spot บน Binance ผู้ใช้สามารถซื้อขายแลกเปลี่ยนเหรียญต่าง ๆ กับผู้ใช้คนอื่น ๆ ได้ ยกตัวอย่างเช่น ผู้ใช้สามารถเข้าไปในตลาด [BNB/USDT](https://www.binance.com/en/trade/BNB_USDT) ใน Binance spot market เพื่อแลกเปลี่ยนเหรียญ BNB ไปเป็นเหรียญ USDT ได้ หรือสามารถใช้ [BNB/BTC](https://www.binance.com/en/trade/BNB_BTC) เพื่อแลกเปลี่ยนเหรียญทั้งสองก็ได้เช่นกัน ตลาด Spot ถือว่าเป็นตลาดที่มีการใช้งานง่ายที่สุด

### การเทรดบน Margin

การเทรดบน Margin คือการเทรดโดยการยืมสินทรัพย์จากบุคคลอื่นในการเทรด ซึ่งจะส่งผลให้ผลลัพธ์การเทรดของเราทวีคูณยิ่งขึ้น ทั้งในทางที่ดีและทางที่เสีย บัญชีประเภท margin จะอนุญาตให้นักเทรดต่าง ๆ สามารถใช้เงินในการเทรดมากกว่าเงินที่ตนมีอยู่จริงได้ นอกจากนี้ยังสามารถทำให้นักเทรดสามารถลดความเสี่ยงจากการบิดพลิ้วของคู่สัญญา \(counterparty risk\) ซึ่งคู่สัญญาในที่นี้ก็คือ exchange ต่าง ๆ นั่นเอง ซึ่งอาจจะโดน hack หรือปิดตัววิ่งหนีไปกับเงินของเราได้ ซึ่งการใช้ margin จะทำให้นักเทรดสามารถเทรดได้เหมือนเดิมแต่ใช้เงินค้ำในบัญชีน้อยลง

มีคำศัพท์อยู่สองตัวที่ได้ยินบ่อย ๆ คือ margin และ leverage คำว่า margin หมายถึงจำนวนเงินทุนที่นักเทรดใช้ค้ำการเทรดต่าง ๆ โดยออกมาจากกระเป๋าของตนเอง คำว่า leverage หมายถึงจำนวนเท่าที่เราใช้คูณจำนวน margin ของเรา เช่น หากนักเทรดใช้ 2x leverage หมายความว่า นักเทรดสามารถเทรดได้ 2 เท่าของจำนวนเงินค้ำ \(margin\) ที่เราวางไว้ในตอนแรก หรือถ้าเป็น 4x leverage ก็จะเทรดได้ 4 เท่า เป็นต้น

การเทรดใน margin จำเป็นที่จะต้องระวังเรื่องการโดน liquidate การใช้ leverage สูง ๆ จะทำให้จุด liquidation กับจุดราคาที่เข้า \(Entry\) ใกล้กันจนเกินไป หากการเทรดของคุณถูก liquidate คุณมีความเสี่ยงที่จะสูญ margin ทั้งหมดที่ได้วางไว้ จึงสมควรจะระวังเรื่องความเสี่ยงที่สูงขึ้นจากการเทรดในแบบ margin ผู้ที่สนใจสามารถอ่านเพิ่มเติมได้จาก [Binance Margin Trading Guide](https://academy.binance.com/en/articles/binance-margin-trading-guide)

การเทรดบน margin ได้รับความนิยมอย่างมากในตลาดหุ้น โภคภัณฑ์ \(commodity\) ตลากแลกเปลี่ยนเงินตรา และรวมไปถึงตลาดบิทคอยน์และคริปโทต่าง ๆ ในตลาดการเงินนอกเหนือจากคริปโท โบรกเกอร์ต่าง ๆ จะเป็นคนปล่อยเงินที่ใช้สำหรับหยิบยืมมาเทรดบน margin ในการเทรดคริปโท มีทั้งแบบที่ exchange เป็นคนปล่อยให้ยืม หรือ แบบที่ผู้ใช้คนอื่น ๆ บน exchange เป็นคนให้ยืม ซึ่งหากเป็นการหยิบยืมจากผู้ใช้คนอื่น มักจะมีอัตราดอกเบี้ยที่ผันผวน ขึ้นอยู่กับความต้องการของตลาด

หากต้องการอ่านเจาะลึกตลาด margin สามารถติดตามได้ที่บทความ [What is Margin Trading?](https://academy.binance.com/en/articles/what-is-margin-trading) ของ Binance Academy

### ตลาดอนุพันธ์ \(Derivatives market\)

ตลาดอนุพันธ์จะอิงมูลค่าของเครื่องมือทางการเงินกับสินทรัพย์ตัวอื่น ๆ ซึ่งอาจจะเป็นสินทรัพย์อื่น ๆ ตัวเดียว หรือว่าเป็นตะกร้าของสินทรัพย์หลาย ๆ ตัวมารวมกันก็ได้ สินทรัพย์ที่นำมาใช้ทำอนุพันธ์บ่อย ๆ คือ ตราสารทุน \(หุ้น\) ตราสารหนี้ \(พันธบัตร\) ดัชนีตลาด และคริปโท

ตัวอนุพันธ์คือสัญญาระหว่างผู้ซื้อผู้ขาย โดยราคาของสินทรัพย์ที่อนุพันธ์นั้น ๆ อ้างอิงจะเป็นตัวกำหนดราคาของอนุพันธ์ ซึ่งมีอนุพันธ์หลาย ๆ แบบ เช่น futures options หรือ swap

ตลาดอนุพันธ์มักจะมีขนาดใหญ่ เนื่องจากการสร้างอนุพันธ์นั้น สามารถใช้สินทรัพย์อะไรเป็นตัวอ้างอิงก็ได้ รวมถึงอนุพันธ์อื่น ๆ อีกด้วย ซึ่งการสร้างอนุพันธ์ซ้อน ๆ กันถูกกล่าวว่าเป็นต้นเหตุของพิษเศรษฐกิจในปี 2008 อีกด้วย

### Forward และ futures contracts

สัญญา Futures คืออนุพันธ์ที่นักเทรดสามารถใช้เก็งกำไรของสินทรัพย์ต่าง ๆ ที่จะเกิดในอนาคตได้ โดยสัญญา Futures จะเป็นข้อตกลงระหว่างผู้ซื้อและผู้ขายเพื่อทำการแลกเปลี่ยนซื้อขายในภายหน้า เรียกว่า วันหมดอายุ \(Expiry date\) โดยสินทรัพย์ที่ใช้เป็นราคาอ้างอิงอาจจะเป็นสินทรัพย์ประเภทใดก็ได้ดังที่ได้กล่าวถึงแล้วในอดีต

วันหมดอายุของ futures คือวันสุดท้ายที่สามารถซื้อขายสัญญาตัวนั้น ๆ ได้ ในวันที่หมดอายุ สัญญา futures จะมีมูลค่าเท่ากับราคาสุดท้ายที่เกิดการซื้อขาย โดยสัญญา futures อาจจะปิดลงได้ด้วยการใช้เงินสด ที่เรียกว่า cash-settled หรือ ปิดด้วยสินทรัพย์ที่ถูกอ้างอิง ที่เรียกว่า physically-delivered \(Tanwa's note: USDT-M เป็น cash-settled และ COIN-M เป็น physically-delivered\)

หากเป็นสัญญาประเภท physically-delivered สินทรัพย์ที่ถูกอ้างอิงจะถูกแลกเปลี่ยนโดยตรง เช่น ต้องมีการส่งน้ำมัน หรือเหรียญคริปโทต่าง ๆ ให้กับผู้ซื้อ เป็นต้น แต่หากเป็น cash-settled จะมีการแลกเปลี่ยนเงินสดให้เท่ากับมูลค่าของสินทรัพย์ในตลาดแทน

สำหรับท่านใดที่เทรดบน Binance สามารถอ่านเพิ่มเติมได้จากบทความ [The Ultimate Guide to Trading on Binance Futures](https://academy.binance.com/en/articles/the-ultimate-guide-to-trading-on-binance-futures)

### Perpetual futures contracts

ตลาด futures เป็นตลาดที่ดีสำหรับเทรดเดอร์ในการเก็งกำไร แต่ถ้าเราอยากเก็งกำไรหลังจากวันที่หมดอายุของ futures แล้วจะทำอย่างไรดี

คำตอบคือ Perpetual futures contract โดยความต่างคือ perpetual futures contract ไม่มีวันหมดอายุ ซึ่งทำให้นักเทรดสามารถเก็งกำไรกับ perp futures ไปได้เรื่อย ๆ โดยไม่ต้องกังวลเรื่องวันหมดอายุ

เนื่องจาก perp futures ไม่มีวันหมดอายุ การที่จะทำให้ราคาของอนุพันธ์ตัวนี้ใกล้เคียงกับราคาที่แท้จริงของสินทรัพย์ที่ถูกอ้างอิงจะมีความสำคัญมาก ไม่อย่างนั้นแล้ว ราคาของ futures อาจจะห่างออกไปจากราคาในตลาด spot มากจนเกินไป

ดังนั้น ตลาด perpetual futures จะมีการเรียกเก็บ funding fee ระหว่างนักเทรดทั้งหลายเอง เช่น ถ้าตลาด futures ราคาสูงกว่าตลาด spot มาก ๆ funding rate จะเป็นบวก ซึ่งทำให้นักเทรดที่ถือ long \(ผู้ซื้อ\) ต้องจ่ายค่า funding ให้กับคนที่ short \(ผู้ขาย\) การจ่ายค่าธรรมเนียมตรงนี้จะเป็นแรงกระตุ้นให้ผู้ซื้อส่วนหนึ่งปิดตำแหน่งเทรด และขาย futures contract เพื่อดันราคาของ futures ให้กลับมาเข้าใกล้ราคาในตลาด spot มากขึ้น ในทางกลับกัน หากราคาในตลาด futures สูงกว่าราคาในตลาด spot นักเทรดที่ short อยู่จะเป็นผู้เสียค่า funding

สรุปคือ หาก funding rate เป็นบวก Long จ่าย short หาก funding เป็นลบ Short จ่าย Long

สามารถอ่านเพิ่มเติมเกี่ยวกับ [What are perpetual futures contracts?](https://academy.binance.com/en/articles/what-are-perpetual-futures-contracts) จาก Binance Academy ได้เลย

### Options contract

สัญญา options คือสัญญาที่ให้สิทธิในการซื้อขายสินทรัพย์ แต่ไม่ใช่สัญญาผูกมัด และการซื้อขายจะเกิดขึ้นในอนาคต ความต่างระหว่าง futures กับ options คือ การซื้อขาย options ไม่ผูกมัดว่าจะต้องมีการปิดสัญญาในอนาคต

นักเทรดจะใช้สัญญา options ในการเก็งกำไรจากทิศทางของราคา

มีสัญญาสองแบบคือ call options และ put options โดย call options ต้องการให้ราคาเพิ่มขึ้น และ put option ต้องการให้ราคาต่ำลง

เช่นเดียวกับอนุพันธ์ตัวอื่น ๆ options สามารถอิงราคาได้จากสินทรัพย์หลากประเภท เช่น ดัชนีตลาด สินค้าโภคภัณฑ์ หุ้น คริปโท เป็นต้น

สัญญา options สามารถใช้เพื่อทำการเทรดใน strategy mี่มีความซับซ้อนมาก ๆ ได้ เช่นการ hedge ความเสี่ยง สำหรับคริปโท options อาจจะเป็นทางเลือกที่ดีในการ hedge ความเสี่ยงสำหรับนักขุดคริปโทต่าง ๆ ซึ่งจะช่วยให้นักขุดสามารถรักษากำไรไว้ได้

### ตลาดแลกเปลี่ยนเงินตราต่างประเทศ \(Forex\)

ตลาดแลกเปลี่ยนเงินตราต่างประเทศ \(Forex หรือ FX\) คือ ตลาดที่นักเทรดสามารถซื้อขายเงินตราระหว่างหลาย ๆ สกุลได้ ซึ่งตลาด FX เป็นตัวกำหนดอัตราแลกเปลี่ยนระหว่างเงินสกุลต่าง ๆ

ถึงแม้สกุลเงินต่าง ๆ จะดูเป็นสินทรัพย์ที่ปลอดภัย แต่ราคาของสกุลเงินเหล่านี้ก็ยังถูกกำหนดด้วยอุปสงค์และอุปทาน จึงสามารถทำให้ราคาเกิดการผันผวนได้ อีกทั้งยังมีเรื่องอัตราเงินเฟ้อ และความมั่นคงทางการค้าขาย ลงทุน และการเมืองระหว่างประเทศเข้ามาร่วมด้วยอีกด้วย

ตลาด FX จะมีคู่การเทรดที่ถูกซื้อขายโดยสถาบันการเงินต่าง ๆ เช่น ธนาคารเพื่อการลงทุน ธนาคารกลาง ธนาคารพาณิชย์ กองทุนรวม หรือแม้แต่นักเทรดรายย่อย ตลาด Forex นึงถูกใช้เป็นตลาดแลกเปลี่ยนซื้อขายระหว่างประเทศ

นักเทรด Forex ส่วนใหญ่เป็นนักเทรดรายวัน \(Day trader\) เช่น การ scalp ด้วย leverage เพื่อเพิ่มผลตอบแทน

ตลาด Forex ถือว่าเป็นหนึ่งในองค์ประกอบหลักของตลาดการเงินสมัยใหม่ที่เรารู้จักและคุ้นเคยกันเป็นอย่างดี รวมทั้งยังเป็นตลาดที่ใหญ่ที่สุดและมีสภาพคล่องมากที่สุดอีกด้วย

### Leveraged tokens

Leverated tokens คือเครื่องมือทางการเงินที่การซื้อขายแลกเปลี่ยนจะถูกคูณด้วย leverage โดยอัตโนมัติ โดยที่ไม่จำเป็นต้องทำการบริหาร leverage เหมือนในตลาด margin และ futures จึงทำให้ไม่ต้องกังวลเรื่อง margin เงินค้ำ ค่า funding หรือการถูก liquidate

Leverated tokens เป็นนวัตกรรมทางการเงินสมัยใหม่ที่ถูกสร้างขึ้นบน blockchain โดย exchange แรกที่ออก leveraged tokens ออกมาคือ FTX โดยคอนเซ็ปต์หลัก ๆ คือ การออก Token ให้กับ leveraged positions ต่าง ๆ

โดย leveraged token จะทำการเปิดไม้เทรดในตลาด perpetual futures และออกเป็น token ออกมาให้ซื้อขาย โดย leveraged token ถือเป็นอนุพันธ์ประเภทหนึ่ง

Leveraged tokens ถือเป็นวิธีที่ง่ายมากในการเทรดแบบมี leverage สามารถอ่านเพิ่มเติมได้ในบทความ [A Beginner's Guide to Binace Leverated Tokens \(BLVT\)](https://academy.binance.com/en/articles/a-beginners-guide-to-binance-leveraged-tokens-blvt)





### 









