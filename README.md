# SimpleShowcaseView

### Library
- [RxAndroid](https://github.com/ReactiveX/RxAndroid)


### Usage

    @Override
    public void onWindowFocusChanged(boolean hasFocus) {
        if (hasFocus) {
            SimpleShowcaseView.Builder builder = new SimpleShowcaseView.Builder(context)
                    .setTarget(targetView)
                    .setHintImageResource(R.drawable.guide_pop_chance)
                    .setHintImageSize(200, 200)
                    .setHintImageDirection(-1, -1)
                    .setDistanceFactor(0.5f);

            SimpleShowcaseView showcaseView = builder.build();
            showcaseView.show();
        }
    }


### Screenshot
![alt tag](https://github.com/dev-chamo/SimpleShowcaseView/blob/master/images/image.png)
