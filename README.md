# Improved-Animations

<style>
@keyframes fadeDown {
    from {
        opacity: 0;
        transform: translate3d(0,-30px,0)
    }

    to {
        opacity: 1;
        transform: none
    }
}

.elementor-element.fadeInDown {
    animation-name: fadeDown
}

@keyframes fadeLeft {
    from {
        opacity: 0;
        transform: translate3d(-30px,0,0)
    }

    to {
        opacity: 1;
        transform: none
    }
}

.elementor-element.fadeInLeft {
    animation-name: fadeLeft
}

@keyframes fadeRight {
    from {
        opacity: 0;
        transform: translate3d(30px,0,0)
    }

    to {
        opacity: 1;
        transform: none
    }
}

.elementor-element.fadeInRight {
    animation-name: fadeRight
}

@keyframes fadeUp {
    from {
        opacity: 0;
        transform: translate3d(0,30px,0)
    }

    to {
        opacity: 1;
        transform: none
    }
}

.elementor-element.fadeInUp {
    animation-name: fadeUp
}
</style>
