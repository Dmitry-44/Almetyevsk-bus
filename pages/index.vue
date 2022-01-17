<template>
	<main class="content">
        <div class="container">
         <div class="content__body">
             <div class="contentInfo">
                 <div class="contentInfo__title">
                     <h2>о нас</h2>
                 </div>
                 <div class="contentInfo__text_1">
                    <p>Поездки осуществляются ежедневно на автобусе опытными водителями со стажем, с прохождением предрейсового медицинского осмотра. 
                        С нами ваша поездка будет комфортной и безопасной.</p>
                    <p>В наши услуги входит доставка ваших посылок, документов и прочих грузов весом до 200 кг в день поездки от точки отправки до точки прибытия.</p>
                 </div>
             </div>
             <div class="content__img"> <img src="/main_car.jpg" alt="автомобиль">
            </div>
         </div>
         <div class="content__text_2">
             <p>
                Расписание и цену поездки на автобус Альметьевск Уфа вы можете узнать в разделе <nuxt-link to="/price" class="link link-page">«Тарифы»</nuxt-link>.
             </p>
             <p>
				На странице	<nuxt-link to="/route" class="link link-page">«Маршрут»</nuxt-link> вы можете узнать, где проезжает и сколько времени уходит на поездку у маршрутного такси Альметьевск Уфа.
            </p>
         </div>
        </div>
    </main>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
