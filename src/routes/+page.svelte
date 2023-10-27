<script lang="ts">
	const heroImage = 'https://tempstorage65070219.blob.core.windows.net/images/hero.png';
	import {
		SmartphoneNfcIcon,
		NfcIcon,
		HardDriveUploadIcon,
		HardDriveDownloadIcon,
		CopyCheckIcon
	} from 'lucide-svelte';
	const macScreenDisplay = 'https://tempstorage65070219.blob.core.windows.net/images/iMac.png';

	const component01Image =
		'https://tempstorage65070219.blob.core.windows.net/images/Component_01.png';
	const component02Image =
		'https://tempstorage65070219.blob.core.windows.net/images/Component_02.png';
	const component03Image =
		'https://tempstorage65070219.blob.core.windows.net/images/Component_03.png';
	const component04Image =
		'https://tempstorage65070219.blob.core.windows.net/images/Component_04.png';
	const component05Image =
		'https://tempstorage65070219.blob.core.windows.net/images/Component_05.png';
	const component06Image =
		'https://tempstorage65070219.blob.core.windows.net/images/Component_06.png';

	const posterImage = 'https://tempstorage65070219.blob.core.windows.net/images/poster.png';
	const ipadFrame = 'https://tempstorage65070219.blob.core.windows.net/images/ipad_frame.png';

	const moreImages = [
		'https://tempstorage65070219.blob.core.windows.net/images/moreImage01.png',
		'https://tempstorage65070219.blob.core.windows.net/images/moreImage02.png',
		'https://tempstorage65070219.blob.core.windows.net/images/moreImage03.png',
		'https://tempstorage65070219.blob.core.windows.net/images/moreImage04.png',
		'https://tempstorage65070219.blob.core.windows.net/images/moreImage05.png'
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

			<div class="flex flex-row gap-8 items-center">
				<a href="https://github.com/misterfocusth/Physical-Computing-Project" target="_blank">
					<button
						class="p-4 bg-[#0D151B] w-72 mt-6 rounded-lg text-white text-lg font-bold py-3 flex flex-row items-center gap-3"
					>
						<svg
							xmlns="http://www.w3.org/2000/svg"
							x="0px"
							y="0px"
							width="36"
							height="36"
							viewBox="0 0 48 48"
						>
							<linearGradient
								id="rL2wppHyxHVbobwndsT6Ca_AZOZNnY73haj_gr1"
								x1="4"
								x2="44"
								y1="23.508"
								y2="23.508"
								gradientUnits="userSpaceOnUse"
								><stop offset="0" stop-color="#4c4c4c" /><stop
									offset="1"
									stop-color="#343434"
								/></linearGradient
							><path
								fill="url(#rL2wppHyxHVbobwndsT6Ca_AZOZNnY73haj_gr1)"
								d="M24,4C12.954,4,4,12.954,4,24c0,8.887,5.801,16.411,13.82,19.016h12.36	C38.199,40.411,44,32.887,44,24C44,12.954,35.046,4,24,4z"
							/><path
								d="M30.01,41.996L30,36.198c0-0.939-0.22-1.856-0.642-2.687c5.641-1.133,8.386-4.468,8.386-10.177	c0-2.255-0.665-4.246-1.976-5.92c0.1-0.317,0.174-0.645,0.22-0.981c0.188-1.369-0.023-2.264-0.193-2.984l-0.027-0.116	c-0.186-0.796-0.409-1.364-0.418-1.388l-0.111-0.282l-0.111-0.282l-0.302-0.032l-0.303-0.032c0,0-0.199-0.021-0.501-0.021	c-0.419,0-1.04,0.042-1.627,0.241l-0.196,0.066c-0.74,0.249-1.439,0.485-2.417,1.069c-0.286,0.171-0.599,0.366-0.934,0.584	C27.334,12.881,25.705,12.69,24,12.69c-1.722,0-3.365,0.192-4.889,0.571c-0.339-0.22-0.654-0.417-0.942-0.589	c-0.978-0.584-1.677-0.819-2.417-1.069l-0.196-0.066c-0.585-0.199-1.207-0.241-1.626-0.241c-0.302,0-0.501,0.021-0.501,0.021	l-0.302,0.032l-0.3,0.031l-0.112,0.281l-0.113,0.283c-0.01,0.026-0.233,0.594-0.419,1.391l-0.027,0.115	c-0.17,0.719-0.381,1.615-0.193,2.983c0.048,0.346,0.125,0.685,0.23,1.011c-1.285,1.666-1.936,3.646-1.936,5.89	c0,5.695,2.748,9.028,8.397,10.17c-0.194,0.388-0.345,0.798-0.452,1.224c-0.197,0.067-0.378,0.112-0.538,0.137	c-0.238,0.036-0.487,0.054-0.739,0.054c-0.686,0-1.225-0.134-1.435-0.259c-0.313-0.186-0.872-0.727-1.414-1.518	c-0.463-0.675-1.185-1.558-1.992-1.927c-0.698-0.319-1.437-0.502-2.029-0.502c-0.138,0-0.265,0.01-0.376,0.028	c-0.517,0.082-0.949,0.366-1.184,0.78c-0.203,0.357-0.235,0.773-0.088,1.141c0.219,0.548,0.851,0.985,1.343,1.255	c0.242,0.133,0.765,0.619,1.07,1.109c0.229,0.368,0.335,0.63,0.482,0.992c0.087,0.215,0.183,0.449,0.313,0.732	c0.47,1.022,1.937,1.924,2.103,2.023c0.806,0.483,2.161,0.638,3.157,0.683l0.123,0.003c0,0,0.001,0,0.001,0	c0.24,0,0.57-0.023,1.004-0.071v2.613c0.002,0.529-0.537,0.649-1.25,0.638l0.547,0.184C19.395,43.572,21.645,44,24,44	c2.355,0,4.605-0.428,6.703-1.176l0.703-0.262C30.695,42.538,30.016,42.422,30.01,41.996z"
								opacity=".05"
							/><path
								d="M30.781,42.797c-0.406,0.047-1.281-0.109-1.281-0.795v-5.804c0-1.094-0.328-2.151-0.936-3.052	c5.915-0.957,8.679-4.093,8.679-9.812c0-2.237-0.686-4.194-2.039-5.822c0.137-0.365,0.233-0.75,0.288-1.147	c0.175-1.276-0.016-2.086-0.184-2.801l-0.027-0.116c-0.178-0.761-0.388-1.297-0.397-1.319l-0.111-0.282l-0.303-0.032	c0,0-0.178-0.019-0.449-0.019c-0.381,0-0.944,0.037-1.466,0.215l-0.196,0.066c-0.714,0.241-1.389,0.468-2.321,1.024	c-0.332,0.198-0.702,0.431-1.101,0.694C27.404,13.394,25.745,13.19,24,13.19c-1.762,0-3.435,0.205-4.979,0.61	c-0.403-0.265-0.775-0.499-1.109-0.699c-0.932-0.556-1.607-0.784-2.321-1.024l-0.196-0.066c-0.521-0.177-1.085-0.215-1.466-0.215	c-0.271,0-0.449,0.019-0.449,0.019l-0.302,0.032l-0.113,0.283c-0.009,0.022-0.219,0.558-0.397,1.319l-0.027,0.116	c-0.169,0.715-0.36,1.524-0.184,2.8c0.056,0.407,0.156,0.801,0.298,1.174c-1.327,1.62-1.999,3.567-1.999,5.795	c0,5.703,2.766,8.838,8.686,9.806c-0.395,0.59-0.671,1.255-0.813,1.964c-0.33,0.13-0.629,0.216-0.891,0.256	c-0.263,0.04-0.537,0.06-0.814,0.06c-0.69,0-1.353-0.129-1.69-0.329c-0.44-0.261-1.057-0.914-1.572-1.665	c-0.35-0.51-1.047-1.417-1.788-1.755c-0.635-0.29-1.298-0.457-1.821-0.457c-0.11,0-0.21,0.008-0.298,0.022	c-0.366,0.058-0.668,0.252-0.828,0.534c-0.128,0.224-0.149,0.483-0.059,0.708c0.179,0.448,0.842,0.85,1.119,1.002	c0.335,0.184,0.919,0.744,1.254,1.284c0.251,0.404,0.37,0.697,0.521,1.067c0.085,0.209,0.178,0.437,0.304,0.712	c0.331,0.719,1.353,1.472,1.905,1.803c0.754,0.452,2.154,0.578,2.922,0.612l0.111,0.002c0.299,0,0.8-0.045,1.495-0.135v3.177	c0,0.779-0.991,0.81-1.234,0.81c-0.031,0,0.503,0.184,0.503,0.184C19.731,43.64,21.822,44,24,44c2.178,0,4.269-0.36,6.231-1.003	C30.231,42.997,30.812,42.793,30.781,42.797z"
								opacity=".07"
							/><path
								fill="#fff"
								d="M36.744,23.334c0-2.31-0.782-4.226-2.117-5.728c0.145-0.325,0.296-0.761,0.371-1.309	c0.172-1.25-0.031-2-0.203-2.734s-0.375-1.25-0.375-1.25s-0.922-0.094-1.703,0.172s-1.453,0.469-2.422,1.047	c-0.453,0.27-0.909,0.566-1.27,0.806C27.482,13.91,25.785,13.69,24,13.69c-1.801,0-3.513,0.221-5.067,0.652	c-0.362-0.241-0.821-0.539-1.277-0.811c-0.969-0.578-1.641-0.781-2.422-1.047s-1.703-0.172-1.703-0.172s-0.203,0.516-0.375,1.25	s-0.375,1.484-0.203,2.734c0.077,0.562,0.233,1.006,0.382,1.333c-1.31,1.493-2.078,3.397-2.078,5.704	c0,5.983,3.232,8.714,9.121,9.435c-0.687,0.726-1.148,1.656-1.303,2.691c-0.387,0.17-0.833,0.33-1.262,0.394	c-1.104,0.167-2.271,0-2.833-0.333s-1.229-1.083-1.729-1.813c-0.422-0.616-1.031-1.331-1.583-1.583	c-0.729-0.333-1.438-0.458-1.833-0.396c-0.396,0.063-0.583,0.354-0.5,0.563c0.083,0.208,0.479,0.521,0.896,0.75	c0.417,0.229,1.063,0.854,1.438,1.458c0.418,0.674,0.5,1.063,0.854,1.833c0.249,0.542,1.101,1.219,1.708,1.583	c0.521,0.313,1.562,0.491,2.688,0.542c0.389,0.018,1.308-0.096,2.083-0.206v3.75c0,0.639-0.585,1.125-1.191,1.013	C19.756,43.668,21.833,44,24,44c2.166,0,4.243-0.332,6.19-0.984C29.585,43.127,29,42.641,29,42.002v-5.804	c0-1.329-0.527-2.53-1.373-3.425C33.473,32.071,36.744,29.405,36.744,23.334z M11.239,32.727c-0.154-0.079-0.237-0.225-0.185-0.328	c0.052-0.103,0.22-0.122,0.374-0.043c0.154,0.079,0.237,0.225,0.185,0.328S11.393,32.806,11.239,32.727z M12.451,33.482	c-0.081,0.088-0.255,0.06-0.389-0.062s-0.177-0.293-0.096-0.381c0.081-0.088,0.255-0.06,0.389,0.062S12.532,33.394,12.451,33.482z M13.205,34.732c-0.102,0.072-0.275,0.005-0.386-0.15s-0.118-0.34-0.016-0.412s0.275-0.005,0.386,0.15	C13.299,34.475,13.307,34.66,13.205,34.732z M14.288,35.673c-0.069,0.112-0.265,0.117-0.437,0.012s-0.256-0.281-0.187-0.393	c0.069-0.112,0.265-0.117,0.437-0.012S14.357,35.561,14.288,35.673z M15.312,36.594c-0.213-0.026-0.371-0.159-0.353-0.297	c0.017-0.138,0.204-0.228,0.416-0.202c0.213,0.026,0.371,0.159,0.353,0.297C15.711,36.529,15.525,36.62,15.312,36.594z M16.963,36.833c-0.227-0.013-0.404-0.143-0.395-0.289c0.009-0.146,0.2-0.255,0.427-0.242c0.227,0.013,0.404,0.143,0.395,0.289	C17.381,36.738,17.19,36.846,16.963,36.833z M18.521,36.677c-0.242,0-0.438-0.126-0.438-0.281s0.196-0.281,0.438-0.281	c0.242,0,0.438,0.126,0.438,0.281S18.762,36.677,18.521,36.677z"
							/>
						</svg>
						<p class="mt-1">Explore on GitHub</p>
					</button>
				</a>

				<a href="#abstract" class="h-full mt-6 font-semibold underline">
					or Scroll to details section
				</a>
			</div>

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
			src="https://www.youtube.com/embed/bK_Bw9ReWZ4?si=ut5PKAU7ZE5RvnwU"
			title="YouTube video player"
			frameborder="0"
			allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
			allowfullscreen
		/>
	</div>

	<div
		class="bg-[url('https://tempstorage65070219.blob.core.windows.net/images/component_sec_bg.png')] bg-center bg-no-repeat bg-cover py-[27%] 2xl:py-[35%]"
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
			<img
				src={'https://tempstorage65070219.blob.core.windows.net/images/ballon.jpg'}
				alt="people"
				class="rounded-full w-48 h-48"
			/>
			<p class="mt-4">นายกิตติภณ ทัศนเปรมสิน</p>
			<p>(65070021)</p>
		</div>

		<div class="font-bold text-xl text-center">
			<img
				src={'https://tempstorage65070219.blob.core.windows.net/images/nun.jpg'}
				alt="people"
				class="rounded-full w-48 h-48"
			/>
			<p class="mt-4">นางสาวขวัญเนตร ถี่ถ้วน</p>
			<p>(65070027)</p>
		</div>
		<div class="font-bold text-xl text-center">
			<img
				src={'https://tempstorage65070219.blob.core.windows.net/images/bamboo.jpg'}
				alt="people"
				class="rounded-full w-48 h-48"
			/>
			<p class="mt-4">นางสาวศรุตา โทรัตน์</p>
			<p>(65070211)</p>
		</div>
		<div class="font-bold text-xl text-center">
			<img
				src={'https://tempstorage65070219.blob.core.windows.net/images/sila.jpg'}
				alt="people"
				class="rounded-full w-48 h-48"
			/>
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
