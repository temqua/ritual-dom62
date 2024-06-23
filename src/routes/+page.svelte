<section>
	<p>
		Ритуальный Дом предлагает полный комплекс ритуальных услуг, непосредственно связанных со смертью, переходом в иной
		мир: погребение, уход за местом захоронения, изготовление всевозможных ритуальных товаров.
	</p>
	<p>Мы предоставим Вам:</p>
	<ul>
		<li>Полный пакет услуг по организации похорон, оформлению захоронения и кремации;</li>
		<li>Организация ритуала прощания,</li>
		<li>Сопровождение похоронной процессии.</li>
		<li>Встреча груза 200 и отправка груза 200.</li>
		<li>Перевозка умершего в другой город или из другого города в г.Рязань.</li>
		<li>Предоставление ритуального транспорта.</li>
		<li>Бальзамирование на дому.</li>
		<li>Продажа гробов от простых до элитных,траурных венков,крестов и др.</li>
		<li>Заказ услуги бригады.</li>
	</ul>
	<p>
		Переход в другой мир, смерть близкого родного человека - это невосполнимая утрата и горе для родных. К этому
		скорбному событию невозможно подготовиться заранее, внезапность случившегося порой лишает сил и выполнение
		необходимых религиозных ритуалов и традиций не представляется возможным.
	</p>
</section>
<section>
	<h1>Каталог</h1>
	<div class="catalogue">
		<img src="https://loremflickr.com/440/320" alt="" class="src" />
		<img src="https://loremflickr.com/440/320" alt="" class="src" />
		<img src="https://loremflickr.com/440/320" alt="" class="src" />
		<img src="https://loremflickr.com/440/320" alt="" class="src" />
	</div>
</section>
<section class="align-center">
	<h1>Контакты</h1>
	<div id="contacts-links">
		<div class="links">
			<a target="_blank" rel="noreferrer" href="https://t.me/cjrecbooking_bot" class="tg-link"></a>
		</div>
		<div class="contact">
			<a href="tel:+79537372555" class="uppercase">+7 953 737 25 55</a>
		</div>
	</div>
</section>
<section class="align-center">
	<h1>Как добраться:</h1>
	<iframe id="map" src="https://yandex.ru/map-widget/v1/?z=12&ol=biz&oid=95289557098" frameborder="0" title="map" />
</section>

<style lang="postcss">
	section {
		display: flex;
		flex-direction: column;
		padding-top: 0.5em;
		margin-left: 3rem;
		margin-right: 3rem;
	}

	h1 {
		text-transform: uppercase;
		text-align: center;
	}

	#map {
		width: 700px;
		height: 400px;
		padding: 0;
		margin: 0;

		@media all and (max-width: 1024px) {
			width: 85vw;
		}
	}

	.catalogue {
		display: flex;
		flex-direction: column;
		gap: 2rem;

		@media (min-width: 768px) {
			flex-direction: row;
			overflow-x: auto;
		}
	}

	.contact {
		padding: 0.7rem;
		font-size: 0.9em;

		.contact a {
			color: white;

			&:hover {
				color: #990e0e;
			}
		}
	}

	#contacts-links {
		display: flex;
		flex-direction: column;
		align-items: center;

		@media (min-width: 768px) {
			flex-direction: row;
		}
	}

	.links {
		position: relative;
		display: inline-flex;
		gap: 0.5em;
		padding: 0.5em;
		min-height: 80px;

		a {
			display: inline-block;
			min-width: 1em;
			background-size: 100%;
			background-repeat: no-repeat;
			background-position: center;
		}
	}

	.tg-link {
		background-image: url('/tg.svg');

		&:hover,
		&:focus {
			background-image: url('/tg-hover.svg');
		}
	}
</style>
