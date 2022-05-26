<template>
<div>
    <div class="intro_block">
        <div class="container">
            <h1>Отвезем вас на комфортабельном автобусе по маршруту<br/>
                <span class="title-sub">Альметьевск - Уфа - Альметьевск</span>
            </h1>
        </div>
    </div>
    <div class="container-app">
        <div class="content">
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
                <div class="content__img">
                    <img src="/main_car.jpg" alt="автомобиль">
                </div>
            </div>
            <div class="content__text_2">
                <p>
                    Расписание и цену поездки на автобус Альметьевск Уфа вы можете узнать в разделе <a href="/price" class="link link-page">«Тарифы»</a>.
                </p>
                <p>
                    На странице	<a href="/route" class="link link-page">«Маршрут»</a> вы можете узнать, где проезжает и сколько времени уходит на поездку у маршрутного такси Альметьевск Уфа.
                </p>
            </div>
            </div>
        </div>
    </div>
</div>
</template>

<script>
export default {
    name: 'IndexPage',
    head() {
        return {
            title: 'Маршрут автобуса Альметьевск - Уфа - Альметьевск',
        }
    }
}
</script>
