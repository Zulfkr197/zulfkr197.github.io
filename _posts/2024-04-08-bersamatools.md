---
title: "BersamaTools"
date: 2024-04-08
description: Tools yang dibuat untuk memudahkan untuk pengguna aplikasi IPOS 5, Print Label, Barcode, Lihat Laku, Melacak Item Laku dan Cek Item
website: #
thumbnail: cover/bersamatools.png
type: Laravel
tools: Figma, VS Code
frontend: Tailwind CSS
backend: PHP, MySQL, PgSQL
---
<div class="post-thumbnail flex flex-col gap-24">

	<section class="splide splide-featured rounded-md bg-thumb rounded-md overflow-hidden border border-bone-outline shadow-sm" aria-label="Slide Background">
		<div class="splide__track">
			<ul class="splide__list">
				<li class="splide__slide">
					<img class="mx-auto" src="cover\bersamatools.png" alt="Bersamatools">
				</li>
				<li class="splide__slide">
					<img class="mx-auto" src="uploads\bersamatools\bersamatools_mobile.png" alt="Bersamatools">
				</li>
			</ul>
		</div>

		<div class="splide__arrows splide__arrows--ltr">
			<button class="splide__arrow splide__arrow--prev" type="button" aria-label="Previous slide" aria-controls="splide01-track" >
				<svg xmlns="http://www.w3.org/2000/svg" class="ionicon w-4 h-4" viewBox="0 0 512 512">
					<path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="48" d="M268 112l144 144-144 144M392 256H100"/>
				</svg>
			</button>
			<button class="splide__arrow splide__arrow--next" type="button" aria-label="Next slide" aria-controls="splide01-track" >
				<svg xmlns="http://www.w3.org/2000/svg" class="ionicon w-4 h-4" viewBox="0 0 512 512">
					<path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="48" d="M268 112l144 144-144 144M392 256H100"/>
				</svg>
			</button>
		  </div>
	</section>

	<div class="flex flex-col lg:flex-row gap-10 lg:gap-16 xl:gap-24">

		<div class="desc lg:max-w-md flex flex-col gap-6 justify-center">
			<h3 class="font-heading font-medium text-slate-800 text-3xl flex items-center gap-5">
				<div class="bg-sky-100 rounded-lg border border-sky-200 flex items-center justify-center size-11">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="currentColor" class="w-5 h-5 text-sky-600">
						<path d="M408 112H106a58 58 0 00-58 58v158a56 56 0 0056 56h8v39.68A40.32 40.32 0 00152.32 464h207.36A40.32 40.32 0 00400 423.68V384h8a56 56 0 0056-56V168a56 56 0 00-56-56zm-40 311.68a8.35 8.35 0 01-8.32 8.32H152.32a8.35 8.35 0 01-8.32-8.32V264.32a8.35 8.35 0 018.32-8.32h207.36a8.35 8.35 0 018.32 8.32zm26-215.76a24 24 0 1122-22 24 24 0 01-22 22zM344 48H168a56.09 56.09 0 00-55.42 48h286.84A56.09 56.09 0 00344 48z"/>
					</svg>
				</div>
				<span>Print Item</span>
			</h3>
			<p class="text-slate-500 text-lg leading-relaxed text-justify">Tools that function to print price tags with several label design options and print barcodes. item data is taken from the PostgresQL IPOS 5 database.</p>
		</div>

		<div class="thumbnail rounded-md bg-thumb rounded-md overflow-hidden border border-bone-outline shadow">
			<div class="bg-bar h-9 flex gap-3 items-center px-4">
				<div class="bg-bar-close rounded-full size-3"></div>
				<div class="bg-bar-minimize rounded-full size-3"></div>
				<div class="bg-bar-maximize rounded-full size-3"></div>
			</div>
			<section class="splide splide-browser max-w-browser" aria-label="Slide Background">
				<div class="splide__track">
					<ul class="splide__list">
						<li class="splide__slide">
							<img class="mx-auto" src="uploads\bersamatools\bersamatools_printitem.png" alt="bersamatools">
						</li>
						<li class="splide__slide">
							<img class="mx-auto" src="uploads\bersamatools\bersamatools_printitem_1.png" alt="bersamatools">
						</li>
						<li class="splide__slide">
							<img class="mx-auto" src="uploads\bersamatools\bersamatools_printitem_2.png" alt="bersamatools">
						</li>
						<li class="splide__slide">
							<img class="mx-auto" src="uploads\bersamatools\bersamatools_printitem_3.png" alt="bersamatools">
						</li>
					</ul>
				</div>
			</section>
		</div>

	</div>

	<div class="flex flex-col lg:flex-row-reverse gap-10 lg:gap-16 xl:gap-24">

		<div class="desc lg:max-w-md flex flex-col gap-6 justify-center">
			<h3 class="font-heading font-medium text-slate-800 text-3xl flex items-center gap-5">
				<div class="bg-cyan-100 rounded-lg border border-cyan-200 flex items-center justify-center size-11">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="currentColor" class="w-5 h-5 text-cyan-600">
						<path d="M64 164v244a56 56 0 0056 56h272a56 56 0 0056-56V164a4 4 0 00-4-4H68a4 4 0 00-4 4zm267 151.63l-63.69 63.68a16 16 0 01-22.62 0L181 315.63c-6.09-6.09-6.65-16-.85-22.38a16 16 0 0123.16-.56L240 329.37V224.45c0-8.61 6.62-16 15.23-16.43A16 16 0 01272 224v105.37l36.69-36.68a16 16 0 0123.16.56c5.8 6.37 5.24 16.29-.85 22.38z"/>
						<rect x="32" y="48" width="448" height="80" rx="32" ry="32"/>
					</svg>
				</div>
				<span>Cek Item</span>
			</h3>
			<p class="text-slate-500 text-lg leading-relaxed text-justify">Tools to check item prices either unit, pack, or quantity. and useful information for cashiers such as cost price (admin only), SKU, Barcode and item discounts.</p>
		</div>

		<div class="thumbnail rounded-md bg-thumb rounded-md overflow-hidden border border-bone-outline shadow">
			<div class="bg-bar h-9 flex gap-3 items-center px-4">
				<div class="bg-bar-close rounded-full size-3"></div>
				<div class="bg-bar-minimize rounded-full size-3"></div>
				<div class="bg-bar-maximize rounded-full size-3"></div>
			</div>
			<img class="mx-auto" src="uploads\bersamatools\bersamatools_cekitem.png" alt="bersamatools">
		</div>

	</div>

	<div class="flex flex-col lg:flex-row gap-10 lg:gap-16 xl:gap-24">

		<div class="desc lg:max-w-md flex flex-col gap-6 justify-center">
			<h3 class="font-heading font-medium text-slate-800 text-3xl flex items-center gap-5">
				<div class="bg-emerald-100 rounded-lg border border-emerald-200 flex items-center justify-center size-11">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="currentColor" class="w-5 h-5 text-emerald-600">
						<path d="M483.82 32.45a16.28 16.28 0 00-11.23 1.37L448 46.1l-24.8-12.4a16 16 0 00-14.31 0l-25.11 12.41L359 33.7a16 16 0 00-14.36 0L320 46.07l-24.45-12.34a16 16 0 00-14.35-.06L256 46.12l-24.8-12.43a16.05 16.05 0 00-14.33 0L192 46.1l-24.84-12.41a16 16 0 00-19.36 3.94 16.25 16.25 0 00-3.8 10.65V288l.05.05H336a32 32 0 0132 32V424c0 30.93 33.07 56 64 56h12a52 52 0 0052-52V48a16 16 0 00-12.18-15.55zM416 240H288.5c-8.64 0-16.1-6.64-16.48-15.28A16 16 0 01288 208h127.5c8.64 0 16.1 6.64 16.48 15.28A16 16 0 01416 240zm0-80H224.5c-8.64 0-16.1-6.64-16.48-15.28A16 16 0 01224 128h191.5c8.64 0 16.1 6.64 16.48 15.28A16 16 0 01416 160z"/><path d="M336 424v-88a16 16 0 00-16-16H48a32.1 32.1 0 00-32 32.05c0 50.55 5.78 71.57 14.46 87.57C45.19 466.79 71.86 480 112 480h245.68a4 4 0 002.85-6.81C351.07 463.7 336 451 336 424z"/>
					</svg>
				</div>
				<span>Struk</span>
			</h3>
			<p class="text-slate-500 text-lg leading-relaxed text-justify">Tools to view cashier receipts, track specific items that have been sold on each transaction on a certain date, view all transactions that use cashless payments.</p>
		</div>

		<div class="thumbnail rounded-md bg-thumb rounded-md overflow-hidden border border-bone-outline shadow">
			<div class="bg-bar h-9 flex gap-3 items-center px-4">
				<div class="bg-bar-close rounded-full size-3"></div>
				<div class="bg-bar-minimize rounded-full size-3"></div>
				<div class="bg-bar-maximize rounded-full size-3"></div>
			</div>
			<img class="mx-auto" src="uploads\bersamatools\bersamatools_struk.png" alt="bersamatools">
		</div>

	</div>

	<div class="flex flex-col lg:flex-row-reverse gap-10 lg:gap-16 xl:gap-24">

		<div class="desc lg:max-w-md flex flex-col gap-6 justify-center">
			<h3 class="font-heading font-medium text-slate-800 text-3xl flex items-center gap-5">
				<div class="bg-red-100 rounded-lg border border-red-200 flex items-center justify-center size-11">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="currentColor" class="w-5 h-5 text-red-600">
						<path d="M448 400H64a16 16 0 010-32h384a16 16 0 010 32zM416 448H96a16 16 0 010-32h320a16 16 0 010 32zM32 272H16v48a32 32 0 0032 32h48v-16a64.07 64.07 0 00-64-64z"/>
						<path d="M480 240h16v-64h-16a96.11 96.11 0 01-96-96V64H128v16a96.11 96.11 0 01-96 96H16v64h16a96.11 96.11 0 0196 96v16h256v-16a96.11 96.11 0 0196-96zm-224 64a96 96 0 1196-96 96.11 96.11 0 01-96 96z"/>
						<circle cx="256" cy="208" r="64"/>
						<path d="M416 336v16h48a32 32 0 0032-32v-48h-16a64.07 64.07 0 00-64 64zM480 144h16V96a32 32 0 00-32-32h-48v16a64.07 64.07 0 0064 64zM96 80V64H48a32 32 0 00-32 32v48h16a64.07 64.07 0 0064-64z"/>
					</svg>
				</div>
				<span>Total Laku</span>
			</h3>
			<p class="text-slate-500 text-lg leading-relaxed text-justify">Tools to view practice reports by today, by time, by date, monthly and annually.</p>
		</div>

		<div class="thumbnail rounded-md bg-thumb rounded-md overflow-hidden border border-bone-outline shadow">
			<div class="bg-bar h-9 flex gap-3 items-center px-4">
				<div class="bg-bar-close rounded-full size-3"></div>
				<div class="bg-bar-minimize rounded-full size-3"></div>
				<div class="bg-bar-maximize rounded-full size-3"></div>
			</div>
			<img class="mx-auto" src="uploads\bersamatools\bersamatools_totallaku.png" alt="bersamatools">
		</div>

	</div>

	<div class="flex flex-col lg:flex-row gap-10 lg:gap-16 xl:gap-24">

		<div class="desc lg:max-w-md flex flex-col gap-6 justify-center">
			<h3 class="font-heading font-medium text-slate-800 text-3xl flex items-center gap-5">
				<div class="bg-orange-100 rounded-lg border border-orange-200 flex items-center justify-center size-11">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" fill="currentColor" class="w-5 h-5 text-orange-600">
						<path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32" d="M352 144h112v112"/>
						<path d="M48 368l121.37-121.37a32 32 0 0145.26 0l50.74 50.74a32 32 0 0045.26 0L448 160" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="32"/>
					</svg>
				</div>
				<span>Trends</span>
			</h3>
			<p class="text-slate-500 text-lg leading-relaxed text-justify">Tools to view the most sold items in a specific period.</p>
		</div>

		<div class="thumbnail rounded-md bg-thumb rounded-md overflow-hidden border border-bone-outline shadow">
			<div class="bg-bar h-9 flex gap-3 items-center px-4">
				<div class="bg-bar-close rounded-full size-3"></div>
				<div class="bg-bar-minimize rounded-full size-3"></div>
				<div class="bg-bar-maximize rounded-full size-3"></div>
			</div>
			<img class="mx-auto" src="uploads\bersamatools\bersamatools_trend.png" alt="bersamatools">
		</div>

	</div>
	
</div>
