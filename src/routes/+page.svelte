<script lang="ts">
	const heroImage =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/hero.png?alt=media&token=f12c1a5a-8584-4d5d-8c67-81cad9fcffa0&_gl=1*bg265y*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2NzE2MS42MC4wLjA.';
	import {
		SmartphoneNfcIcon,
		NfcIcon,
		HardDriveUploadIcon,
		HardDriveDownloadIcon,
		CopyCheckIcon
	} from 'lucide-svelte';
	const macScreenDisplay =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/iMac.png?alt=media&token=3cf90a2c-930b-4c1d-9994-7b085391bc49&_gl=1*15ym3we*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2NzE2OS41Mi4wLjA.';

	const component01Image =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/Component_01.png?alt=media&token=5e020851-d280-48ee-ae36-17e4a5e9a124&_gl=1*1e8tm5x*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2Njk5Mi4xNC4wLjA.';
	const component02Image =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/Component_02.png?alt=media&token=5e020851-d280-48ee-ae36-17e4a5e9a124&_gl=1*1e8tm5x*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2Njk5Mi4xNC4wLjA.';
	const component03Image =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/Component_03.png?alt=media&token=5e020851-d280-48ee-ae36-17e4a5e9a124&_gl=1*1e8tm5x*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2Njk5Mi4xNC4wLjA.';
	const component04Image =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/Component_04.png?alt=media&token=5e020851-d280-48ee-ae36-17e4a5e9a124&_gl=1*1e8tm5x*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2Njk5Mi4xNC4wLjA.';
	const component05Image =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/Component_05.png?alt=media&token=5e020851-d280-48ee-ae36-17e4a5e9a124&_gl=1*1e8tm5x*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2Njk5Mi4xNC4wLjA.';
	const component06Image =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/Component_06.png?alt=media&token=5e020851-d280-48ee-ae36-17e4a5e9a124&_gl=1*1e8tm5x*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2Njk5Mi4xNC4wLjA.';

	const posterImage =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/poster.png?alt=media&token=30deee74-c1d6-45a6-a636-f3213b6847ed&_gl=1*7825in*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2NzE4NS4zNi4wLjA.';
	const ipadFrame =
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/ipad_frame.png?alt=media&token=9f63f693-87b7-4b23-9082-4974130a13b3&_gl=1*jpag39*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2NzE3Ny40NC4wLjA.';

	const moreImages = [
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/moreImage01.png?alt=media&token=7dc560bc-8de5-498a-9f9e-222be399710a&_gl=1*hqhxhn*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI5OTM0NC4yLjEuMTY5ODI5OTg5My4yOC4wLjA.',
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/moreImage02.png?alt=media&token=7cae3e65-4116-4bc6-912f-6c7c9f1df0e4&_gl=1*104tyai*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI5OTM0NC4yLjEuMTY5ODI5OTkyMi42MC4wLjA.',
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/moreImage03.png?alt=media&token=7cae3e65-4116-4bc6-912f-6c7c9f1df0e4&_gl=1*104tyai*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI5OTM0NC4yLjEuMTY5ODI5OTkyMi42MC4wLjA.',
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/moreImage04.png?alt=media&token=7cae3e65-4116-4bc6-912f-6c7c9f1df0e4&_gl=1*104tyai*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI5OTM0NC4yLjEuMTY5ODI5OTkyMi42MC4wLjA.',
		'https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/moreImage05.png?alt=media&token=7cae3e65-4116-4bc6-912f-6c7c9f1df0e4&_gl=1*104tyai*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI5OTM0NC4yLjEuMTY5ODI5OTkyMi42MC4wLjA.'
	];
</script>

<header class="p-6 px-12 flex flex-row justify-between">
	<p class="font-bold text-xl">JOK</p>
	<div class="flex flex-row gap-6 font-semibold">
		<a href="#abstract">ABSTRACT</a>
		<a href="#description">DESCRIPTION</a>
		<a href="#demo">DEMO</a>
		<a href="#components">COMPONENTS & PROGRAMS</a>
		<a href="#poster">POSTER</a>
		<a href="#members">TEAM MEMBERS</a>
	</div>
</header>

<main class="pb-12">
	<div class="flex flex-row justify-between items-center relative min-w-full">
		<div class="pl-12 mt-[15%]">
			<p class="text-[96px] font-bold">ULTRASONIC</p>
			<p class="text-[96px] font-bold special-font">SENSOR RADAR</p>
			<p class="text-[24px] my-2">MY RADAR, YOUR EYES</p>

			<a href="#abstract">
				<button class="p-4 bg-[#0D151B] w-56 mt-4 rounded-lg text-white text-xl font-bold py-3"
					>START!</button
				>
			</a>

			<img src={heroImage} alt="hero" class="w-[60%] absolute right-0 top-0" />
		</div>
	</div>

	<p class="text-5xl font-bold text-center mt-[25%] scroll-m-12" id="abstract">
		ABSTRACT (บทคัดย่อ)
	</p>

	<div class="p-8 m-24 mt-16 shadow rounded-3xl text-lg bg-white flex flex-col gap-4">
		<p>
			<span class="font-bold"> โปรเจ็คจ๊อก (Jok) </span> เป็นเครื่องมือที่ใช้ในการตรวจจับระยะของวัตถุที่อยู่ใกล้กับผู้ใช้
			โดยอาศัยเทคนิคเเละหลักการของคลื่นอัลตราโซนิก (Ultrasonic) เเละการทำงานของเซนเซอร์อัลตราโซนิก (Ultrasonic
			Sensor) เป็นการใช้คลื่นเสียงความถี่สูง (คลื่นอัลตราโซนิก) เพื่อตรวจจับระยะห่างระหว่างเซนเซอร์กับวัตถุหรือผู้ใช้
		</p>

		<p>
			หลักการทำงานของอุปกรณ์มีขั้นตอนการทำงานดังนี้ ส่งสัญญาณอัลตราโซนิก:
			เซนเซอร์อัลตราโซนิกส่งคลื่นเสียงอัลตราโซนิกออกจากขนาดของพายตรงหน้าเซนเซอร์ (transducer)
			ส่งคลื่นไปยังวัตถุ: คลื่นอัลตราโซนิกที่ส่งออกจะเจอวัตถุที่อยู่ข้างหน้า
			เมื่อคลื่นชนเข้ากับวัตถุนั้น คลื่นจะถูกสะท้อนกลับไปที่เซนเซอร์ รับคลื่นที่สะท้อน:
			ส่วนรับคลื่นของเซนเซอร์จะรับคลื่นที่สะท้อนกลับมาจากวัตถุและแปลงคลื่นเหล่านี้เป็นสัญญาณไฟฟ้า
			วัดเวลาการกลับมา:
			เซนเซอร์จะวัดระยะห่างระหว่างตัวเซนเซอร์และวัตถุโดยการวัดเวลาที่คลื่นอัลตราโซนิกใช้ในการเดินทางไปกลับระหว่างเซนเซอร์และวัตถุ
			ส่งข้อมูล:
			ระยะห่างที่วัดได้จะถูกส่งไปยังไมโครคอน๊ทรอลเลอร์หรือคอมพิวเตอร์เพื่อประมวลผลข้อมูลและใช้ในแอปลิเคชันหรือโปรเจกต์ต่าง
			ๆ ตามการใช้งานที่กำหนดไว้
		</p>

		<p>
			อุปกรณ์ที่ใช้ในการพัฒนาได้เเก่ 1.Arduino MEGA 2560 R3 2.Ultrasonic Sensor HC-SR04 3.MG90S
			Tower Pro Metal Gear Servo Motor 4.Mounting Bracket for HC-SR04 5.Jumper (M2F) 30cm Male to
			Female 6.Jumper (M2M) 10cm 2.54mm Male to Male เเละโปรเเกรมที่ใช้ในการพัฒนาได้เเก่ 1.Arduino
			IDE เเละ 2.Pocessing
		</p>
	</div>

	<div class="pl-12 text-5xl font-bold flex flex-col gap-4 scroll-m-12" id="description">
		<p>DESCRIPTION</p>
		<p>(การทำงานของอุปกรณ์)</p>
	</div>

	<div class="px-12 flex flex-row items-center gap-2 justify-between">
		<div class="w-2/12 bg-[#D76263] p-6 rounded-3xl min-h-[35vh] text-lg">
			<span class="font-bold">ส่งสัญญาณอัลตราโซนิก</span>:
			เซนเซอร์อัลตราโซนิกส่งคลื่นเสียงอัลตราโซนิกออก จากขนาดของพายตรงหน้าเซนเซอร์ (transducer)
			<NfcIcon size={72} class="mx-auto mt-12" />
		</div>
		<div class="w-2/12 bg-[#A5E3F9] p-6 mt-48 rounded-3xl min-h-[35vh] text-lg">
			<SmartphoneNfcIcon size={72} class="mx-auto mb-12 mt-6" />
			<span class="font-bold">ส่งคลื่นไปยังวัตถุ</span>: :
			คลื่นอัลตราโซนิกที่ส่งออกจะเจอวัตถุที่อยู่ข้างหน้า เมื่อคลื่นชนเข้ากับวัตถุนั้น
			คลื่นจะถูกสะท้อนกลับไปที่เซนเซอร์
		</div>
		<div class="w-2/12 bg-[#AB9EEC] p-6 rounded-3xl min-h-[35vh] text-lg">
			<span class="font-bold">ส่งข้อมูล</span>: ระยะห่างที่วัดได้จะถูก ส่งไปยังไมโคร
			คอนโทรอลเลอร์หรือ คอมพิวเตอร์เพื่อประมวลผลข้อมูลและใช้ในแอปลิเคชันหรือโปรเจกต์ต่าง ๆ
			ตามการใช้งานที่กำหนดไว้
			<HardDriveUploadIcon size={72} class="mx-auto mt-12" />
		</div>
		<div class="w-2/12 bg-[#EAB95D] p-6 mt-48 rounded-3xl min-h-[35vh] text-lg">
			<HardDriveDownloadIcon size={72} class="mx-auto mb-12 mt-6" />
			<span class="font-bold">รับคลื่นที่สะท้อน</span>:
			ส่วนรับคลื่นของเซนเซอร์จะรับคลื่นที่สะท้อนกลับมาจากวัตถุและแปลงคลื่นเหล่านี้เป็นสัญญาณไฟฟ้า
		</div>
		<div class="w-2/12 bg-[#D76263] p-6 rounded-3xl min-h-[35vh] text-lg">
			<span class="font-bold">วัดเวลาการกลับมา</span>
			เซนเซอร์จะวัดระยะห่าง ระหว่างตัวเซนเซอร์และวัตถุโดยการวัดเวลาที่คลื่น อัลตราโซนิกใช้ในการ เดินทางไปกลับ
			ระหว่างเซนเซอร์และวัตถุ
			<CopyCheckIcon size={72} class="mx-auto mt-12" />
		</div>
	</div>

	<div class="text-5xl font-bold flex flex-col gap-4 text-center mt-24 scroll-m-12" id="demo">
		<p>DEMO CLIP</p>
		<p>(วิดีโอการสาธิตการใช้งาน)</p>
	</div>

	<div class="relative">
		<img src={macScreenDisplay} alt="mac" class="w-[65%] mx-auto mt-16" />
		<iframe
			class="absolute top-[7%] left-[20%]"
			width="60%"
			height="62%"
			src="https://www.youtube.com/embed/TAkmNrteM4I?si=_J7L4edTZhAJMOCt"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
	</div>

	<div
		class="bg-[url('https://firebasestorage.googleapis.com/v0/b/webrtc-firebase-f1d8e.appspot.com/o/component_sec_bg.png?alt=media&token=13a938ab-8154-43c9-b74d-cb30d2f5a65b&_gl=1*1wjrz69*_ga*NzM1NjI2ODEzLjE2OTgyNjY4ODE.*_ga_CW55HF8NVT*MTY5ODI2Njg4MS4xLjEuMTY5ODI2NzIyMi42MC4wLjA.')] bg-center bg-no-repeat bg-cover py-[27%] 2xl:py-[35%]"
	>
		<div class="pl-12 text-5xl font-bold flex flex-col gap-4 mt-24 scroll-m-12" id="components">
			<p>COMPONENTS</p>
			<p>(อุปกรณ์และโปรแกรมที่ใช้ในการพัฒนา)</p>
		</div>
		<div class="px-12 mt-36 flex flex-row gap-8 justify-around">
			<div
				class="shadow rounded-3xl bg-white max-w-[25vw] min-w-[25vw] p-4 text-xl font-bold text-center relative h-[25vh]"
			>
				<img src={component01Image} alt="component" class="absolute top-[-50%] w-56 right-[15%]" />
				<p class="mt-[30%] break-all text-3xl">Arduino UNO R3</p>
			</div>
			<div
				class="shadow rounded-3xl bg-white max-w-[25vw] min-w-[25vw] p-4 text-xl font-bold text-center relative h-[25vh]"
			>
				<img src={component02Image} alt="component" class="absolute top-[-50%] w-56 right-[15%]" />
				<p class="mt-[30%] break-all text-3xl">Ultrasonic Sensor HC-SR04</p>
			</div>
			<div
				class="shadow rounded-3xl bg-white max-w-[25vw] min-w-[25vw] p-4 text-xl font-bold text-center relative h-[25vh]"
			>
				<img src={component03Image} alt="component" class="absolute top-[-50%] w-64 right-[15%]" />
				<p class="mt-[30%] break-all text-3xl">Mounting Bracket for HC-SR04</p>
			</div>
		</div>

		<div class="px-12 mt-24 flex flex-row gap-8 justify-around">
			<div
				class="shadow rounded-3xl bg-white max-w-[25vw] min-w-[25vw] p-4 text-xl font-bold text-center relative h-[25vh]"
			>
				<img src={component04Image} alt="component" class="absolute top-[-40%] w-56 right-[15%]" />
				<p class="mt-[30%] break-all text-3xl">MG90S Tower Pro Metal Gear Servo Motor</p>
			</div>
			<div
				class="shadow rounded-3xl bg-white max-w-[25vw] min-w-[25vw] p-4 text-xl font-bold text-center relative h-[25vh]"
			>
				<img src={component05Image} alt="component" class="absolute top-[-30%] w-56 right-[15%]" />
				<p class="mt-[30%] break-all text-3xl">Jumper (M2M) 10cm 2.54mm Male to Male</p>
			</div>
			<div
				class="shadow rounded-3xl bg-white max-w-[25vw] min-w-[25vw] p-4 text-xl font-bold text-center relative h-[25vh]"
			>
				<img src={component06Image} alt="component" class="absolute top-[-55%] w-64 right-[15%]" />
				<p class="mt-[30%] break-all text-3xl">Jumper (M2F) 30cm Male to Female</p>
			</div>
		</div>
	</div>

	<div class="pl-12 text-5xl font-bold flex flex-col gap-4 scroll-m-12" id="programs">
		<p>PROGRAMS</p>
		<p>(โปรเเกรมที่ใช้ในการพัฒนา)</p>
	</div>

	<div class="px-12 mt-16 flex flex-row gap-12">
		<img
			src="https://europe1.discourse-cdn.com/arduino/original/4X/b/9/7/b97eba49c5b2fea76458b66b669a53d4fb09a389.png"
			alt="ide"
			class="w-1/2"
		/>
		<div class="bg-white rounded-3xl w-full p-8">
			<div class="flex flex-row items-center gap-4">
				<img
					src="https://www.arduino.cc/wiki/370832ed4114dd35d498f2f449b4781e/arduino.svg"
					alt="icon"
					class="w-16"
				/>
				<p class="font-bold text-xl">Arduino IDE</p>
			</div>
			<p class="mt-6 text-lg">
				Arduino IDE (Integrated Development Environment) คือโปรแกรมที่ใช้ในการพัฒนาและโปรแกรมบอร์ด
				Arduino ได้อย่างง่ายและรวดเร็ว โดยสำหรับการพัฒนาโปรแกรมหรือโค้ดสำหรับบอร์ด Arduino
				และบอร์ดที่เกี่ยวข้องอื่น ๆ ซึ่งใช้ไมโครคอนโทรลเลอร์เบอร์ตราที่ชื่อ Arduino
				ในการควบคุมอุปกรณ์ต่าง ๆ อย่างง่าย
				เป็นสิ่งที่ช่วยนักพัฒนาโปรแกรมหรือผู้เริ่มต้นในการเริ่มต้นที่สะดวกและมีความเข้าใจง่าย
				เนื่องจากมีหลายคำสั่งและไลบรารีที่มาพร้อมให้ใช้งานในอินเตอร์เฟซกราฟิกและอุปกรณ์สื่อสารต่าง ๆ
				ใน Arduino IDE อีกทั้งยังมีเครื่องมือในการอัปโหลดโปรแกรมลงบอร์ด Arduino
				และจำลองการทำงานของโค้ดก่อนที่จะอัปโหลดไปยังบอร์ดจริง ๆ
				ซึ่งทำให้การพัฒนาและทดสอบโปรแกรมเป็นไปอย่างรวดเร็วและมีประสิทธิภาพสูง เพื่อให้บอร์ด Arduino
				ทำงานตามที่คุณต้องการ.
			</p>
		</div>
	</div>

	<div class="px-12 mt-16 flex flex-row gap-12">
		<div class="bg-white rounded-3xl w-full p-8">
			<div class="flex flex-row items-center gap-4">
				<img
					src="data:image/png;base64,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"
					alt="icon"
					class="w-16"
				/>
				<p class="font-bold text-xl">Processing</p>
			</div>
			<p class="mt-6 text-lg">
				Processing เป็นซอฟต์แวร์ที่ใช้สำหรับการพัฒนาและสร้างกราฟิก 2D และ 3D
				รวมถึงสื่ออินเตอร์แอคทีฟต่าง ๆ แบบสตรีมและแบบแบ็ทช์ โดย Processing
				ถูกพัฒนาขึ้นเพื่อเป็นเครื่องมือที่ง่ายต่อการสร้างกราฟิกและสร้างภาพการเครื่องดนตรี
				นอกจากนี้ยังมีฟังก์ชันการเขียนโปรแกรมคอมพิวเตอร์กราฟิกแบบอินเตอร์แอคทีฟและการสร้างแอพลิเคชันเพื่อการแสดงผลและการสื่อสารทางสื่อดิจิตอลต่าง
				ๆ
			</p>
		</div>
		<img
			src="https://miro.medium.com/v2/resize:fit:1400/1*incnh913YGKkSY9nmUJYLQ.gif"
			alt="ide"
			class="w-1/2"
		/>
	</div>

	<p class="text-5xl font-bold text-center mt-24 scroll-m-12" id="poster">POSTER</p>
	<div class="relative">
		<img src={ipadFrame} alt="frame" class="w-[50%] 2xl:w-[40%] mx-auto mt-16" />
		<img
			src={posterImage}
			alt="poster"
			class="mt-16 max-w-xl mx-auto absolute top-[0%] right-[30%] 2xl:right-[33%] 2xl:top-[-2%]"
		/>
	</div>

	<div class="pl-12 text-5xl font-bold flex flex-col gap-4 scroll-m-12 mt-24" id="members">
		<p>รูปภาพชิ้นงานเพิ่มเติม</p>
	</div>

	<div
		class="carousel carousel-center h-80 p-4 space-x-4 bg-neutral rounded-box mt-16 flex justify-center mx-16"
	>
		<div class="carousel-item">
			<img src={moreImages[0]} class="rounded-box" alt="more" />
		</div>
		<div class="carousel-item">
			<img src={moreImages[1]} class="rounded-box" alt="more" />
		</div>
		<div class="carousel-item">
			<img src={moreImages[2]} class="rounded-box" alt="more" />
		</div>
		<div class="carousel-item">
			<img src={moreImages[3]} class="rounded-box" alt="more" />
		</div>
		<div class="carousel-item">
			<img src={moreImages[4]} class="rounded-box" alt="more" />
		</div>
	</div>

	<div
		class="pl-12 text-5xl font-bold flex flex-col text-center gap-4 scroll-m-12 mt-24"
		id="members"
	>
		<p>TEAM MEMBERS</p>
		<p>(สมาชิกกลุ่ม)</p>
	</div>

	<div class="flex flex-row gap-2 justify-around px-12 mt-16">
		<div class="font-bold text-xl text-center">
			<img src={posterImage} alt="people" class="rounded-full w-48 h-48" />
			<p class="mt-4">นายศิลา ภักดีวงษ์</p>
			<p>(65070219)</p>
		</div>

		<div class="font-bold text-xl text-center">
			<img src={posterImage} alt="people" class="rounded-full w-48 h-48" />
			<p class="mt-4">นายศิลา ภักดีวงษ์</p>
			<p>(65070219)</p>
		</div>

		<div class="font-bold text-xl text-center">
			<img src={posterImage} alt="people" class="rounded-full w-48 h-48" />
			<p class="mt-4">นายศิลา ภักดีวงษ์</p>
			<p>(65070219)</p>
		</div>

		<div class="font-bold text-xl text-center">
			<img src={posterImage} alt="people" class="rounded-full w-48 h-48" />
			<p class="mt-4">นายศิลา ภักดีวงษ์</p>
			<p>(65070219)</p>
		</div>
	</div>
</main>

<footer class="text-sm p-8 bg-white text-center flex flex-col gap-2">
	<p>This project is a part of Physical Computing (06016409) subject.</p>
	<p>
		Created with ❤️ at School of Information Technology, King Mongkut's Institite of Technology
		Ladkrabang.
	</p>
</footer>
