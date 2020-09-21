# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [4.0.0-alpha.14](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.13...vee-validate@4.0.0-alpha.14) (2020-09-20)


### Bug Fixes

* **core:** in case of radio or checkbox explicitly set initialValue ([#2907](https://github.com/logaretm/vee-validate/issues/2907)) ([e45ec82](https://github.com/logaretm/vee-validate/commit/e45ec82ee8fa6fabd4d3012a03ba8f9b72854631))


### Features

* use symbols to avoid provide/inject conflicts ([cc80032](https://github.com/logaretm/vee-validate/commit/cc8003213c34a8a33d84802f2c93598e1ac3c6f0))
* workspaces ([#2904](https://github.com/logaretm/vee-validate/issues/2904)) ([0c05f94](https://github.com/logaretm/vee-validate/commit/0c05f9486a73744273de6816f00f689916aba91c))





# [4.0.0-alpha.13](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.12...vee-validate@4.0.0-alpha.13) (2020-09-16)


### Features

* nested objects/arrays ([#2897](https://github.com/logaretm/vee-validate/issues/2897)) ([8d161a1](https://github.com/logaretm/vee-validate/commit/8d161a137a65c90ec8f7189743be24802231cf29))





# [4.0.0-alpha.12](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.11...vee-validate@4.0.0-alpha.12) (2020-09-15)


### Features

* cast single checkboxes values to booleans closes [#2889](https://github.com/logaretm/vee-validate/issues/2889) ([7a08184](https://github.com/logaretm/vee-validate/commit/7a081845ac6a4bc09c51e52c5996b65814a48baf))
* invoke generateMessage handler for local functions closes [#2893](https://github.com/logaretm/vee-validate/issues/2893) ([e9fe773](https://github.com/logaretm/vee-validate/commit/e9fe77365877edda51548c9539ec085fff91586b))





# [4.0.0-alpha.11](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.10...vee-validate@4.0.0-alpha.11) (2020-09-02)

**Note:** Version bump only for package vee-validate





# [4.0.0-alpha.10](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.9...vee-validate@4.0.0-alpha.10) (2020-08-29)


### Bug Fixes

* added temporary fix for [#2873](https://github.com/logaretm/vee-validate/issues/2873) with form meta ([6e1bf17](https://github.com/logaretm/vee-validate/commit/6e1bf176e7ba5c890afab6c11731dac54924d39b))





# [4.0.0-alpha.9](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.8...vee-validate@4.0.0-alpha.9) (2020-08-28)


### Bug Fixes

* adapt to the breaking changes in #vue-1682 closes [#2873](https://github.com/logaretm/vee-validate/issues/2873) ([05f7df3](https://github.com/logaretm/vee-validate/commit/05f7df313f9f47ca79bdf99be35cb2ccfea0c346))





# [4.0.0-alpha.8](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.7...vee-validate@4.0.0-alpha.8) (2020-08-13)


### Bug Fixes

* detect initial values from v-model ([e566302](https://github.com/logaretm/vee-validate/commit/e566302bb485353f03baccdf98f35a255605e15d))
* handle unmount issue when removed value is falsy for checkboxes ([b6393f4](https://github.com/logaretm/vee-validate/commit/b6393f4adce9346cadaf1f423dca29645bf3c2f1))
* initial array values for checkboxes not populated correctly in form ([fb99edc](https://github.com/logaretm/vee-validate/commit/fb99edc309c26f9be2baa71f90ec1ac59ddcdc9d))
* umounting group of checkbox issues ([8c77af5](https://github.com/logaretm/vee-validate/commit/8c77af52955b235a6bd2357a35036097e109e37f))


### Features

* added basic v-model support ([c93d125](https://github.com/logaretm/vee-validate/commit/c93d125b4d6c0af8365920ee577c883493e60648))
* merge ctx.attrs to any rendered root node ([5c9979c](https://github.com/logaretm/vee-validate/commit/5c9979ce45d4ab10cd019ad0c25159e013198301))
* sync the model value with inner value ([57d7923](https://github.com/logaretm/vee-validate/commit/57d79232f490be3525c2576ef83376a2f5643386))





# [4.0.0-alpha.7](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.6...vee-validate@4.0.0-alpha.7) (2020-08-04)


### Bug Fixes

* avoid removing array value for a non-group field closes [#2847](https://github.com/logaretm/vee-validate/issues/2847) ([69f2092](https://github.com/logaretm/vee-validate/commit/69f2092db7d53665986dd384cae561d1b13bd8f5))
* bails affects yup non-object validators ([a50645b](https://github.com/logaretm/vee-validate/commit/a50645b1c0206d0e7d85ec6681ff6dc224536fa2))
* initial values on HTML inputs ([c4f4eb9](https://github.com/logaretm/vee-validate/commit/c4f4eb9fe97b13fedb93ac760614eb53c177ffb3))


### Features

* deprecate the skipOptional config ([e62f5ea](https://github.com/logaretm/vee-validate/commit/e62f5ea6d31e82ac9f257627e8544431b933c4f9))





# [4.0.0-alpha.6](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.5...vee-validate@4.0.0-alpha.6) (2020-07-27)


### Bug Fixes

* render input tags by default for the field component ([858c47b](https://github.com/logaretm/vee-validate/commit/858c47b4a7fa740611abaf026e6e5db6cdb41050))





# [4.0.0-alpha.5](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.4...vee-validate@4.0.0-alpha.5) (2020-07-24)


### Bug Fixes

* unregister fields once they are unmounted ([0d601cb](https://github.com/logaretm/vee-validate/commit/0d601cb60b3ba907e6c0d73dd129c0c7b086316e))


### Features

* **v4:** add checkbox and radio HTML input support ([#2835](https://github.com/logaretm/vee-validate/issues/2835)) ([ab3d499](https://github.com/logaretm/vee-validate/commit/ab3d4998caf5950656dc0476f13215d598b28832))
* render input by default for the field component ([81d055d](https://github.com/logaretm/vee-validate/commit/81d055d704deaa12b392fd9197218733b3a0bb8d))





# [4.0.0-alpha.4](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.3...vee-validate@4.0.0-alpha.4) (2020-07-23)

**Note:** Version bump only for package vee-validate





# [4.0.0-alpha.3](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.2...vee-validate@4.0.0-alpha.3) (2020-07-21)


### Features

* automatic injection of the form controller ([c039831](https://github.com/logaretm/vee-validate/commit/c0398318ec70c925b6bcb2afa859ec89488e1f78))
* remove debounce feature and make it userland ([b7263ce](https://github.com/logaretm/vee-validate/commit/b7263ce0f887388709846975b59965e440636089))





# [4.0.0-alpha.2](https://github.com/logaretm/vee-validate/compare/vee-validate@4.0.0-alpha.1...vee-validate@4.0.0-alpha.2) (2020-07-19)


### Features

* always render a from by default ([402603a](https://github.com/logaretm/vee-validate/commit/402603a8f755a377a056debf24815611a01c3037))





# 4.0.0-alpha.1 (2020-07-18)


### Bug Fixes

* added check for cross-fields extraction on unsupported schema ([0ff1bad](https://github.com/logaretm/vee-validate/commit/0ff1bad84a90189f11897cada01fd091e5593bb7))
* added errorMessage prop to the field type ([f1553d0](https://github.com/logaretm/vee-validate/commit/f1553d01b94a74580700fd8712b67688f9c89c15))
* added single error message prop to the provider slot props ([bc97d0c](https://github.com/logaretm/vee-validate/commit/bc97d0c6463cd7e466bb7b3555671e7891d4c60b))
* added unwrap util function ([121bffc](https://github.com/logaretm/vee-validate/commit/121bffc05a9c6e2e204b843d5eb8d7678e5d0fff))
* adjust the useField options to be less strict ([7ea8263](https://github.com/logaretm/vee-validate/commit/7ea826373a78b4fa6343f1da9db0e43879fa0e4e))
* check if a form is present before accessing its schema ([3656181](https://github.com/logaretm/vee-validate/commit/3656181b17a6e44c8f470570ee5126cf2a83ae41))
* debouncing not working correctly and move it to hoc only ([86280a1](https://github.com/logaretm/vee-validate/commit/86280a15e9fb1f94ef8c042a9d04d437f38936b0))
* ensure we unwrap the field id if it was reactive ([7f91e93](https://github.com/logaretm/vee-validate/commit/7f91e930ec8cce4f2e17b49ee9d642d7e9343d6f))
* initial validation not respecting the config opts ([2443d44](https://github.com/logaretm/vee-validate/commit/2443d44b1b00eda39ff884f33f85414aa2b1d34e))
* localization default fallback not being interpolated correctly ([165e89c](https://github.com/logaretm/vee-validate/commit/165e89c6136126d6b946640623261f32b299a2a3))
* no clue why this isn't building ([0d3e7fd](https://github.com/logaretm/vee-validate/commit/0d3e7fdea6f28e29d25f488cae527e925608da7e))
* only add novalidate attr if the rendered element is form ([3638cea](https://github.com/logaretm/vee-validate/commit/3638cead19c9501783e23b43248ce49d7bdf51d7))
* param mapping causing target names to resolve incorrectly ([fb77dc6](https://github.com/logaretm/vee-validate/commit/fb77dc673cb1eff72a1508cff7b4aaed60d8450e))
* set pending back to false earlier in the cycle ([a4237a2](https://github.com/logaretm/vee-validate/commit/a4237a2f8dfde5efcc1d39b5a400e988b8740df9))
* temporary fix for the unamed import issue with vue-beta 4 ([62d27e9](https://github.com/logaretm/vee-validate/commit/62d27e9c9293026d26d62709c2e691d3eb15753e))
* unwrap flags before sending them to the observer slot ([19f7886](https://github.com/logaretm/vee-validate/commit/19f7886adae59b4442139f6e1a3f3905ab54f86a))
* use the proper model event name ([5704db8](https://github.com/logaretm/vee-validate/commit/5704db879019b89b001f496f5f113df24ad09bc6))
* watch target fields once they change ([a4184b0](https://github.com/logaretm/vee-validate/commit/a4184b0065c26df77b680cfbda7450a81b6764ef))


### Features

* adapt the changes from the v3 master branch ([2301c5a](https://github.com/logaretm/vee-validate/commit/2301c5ae75eb8590cb2cc919215ffe4ae934b885))
* add name resolution from v3 ([ba77fdd](https://github.com/logaretm/vee-validate/commit/ba77fdde4f7e5400c6755331af4705715ecc885b))
* add native submit alternative to handleSubmit ([bc00888](https://github.com/logaretm/vee-validate/commit/bc008880607f0393c4e6bd9eb2d44ebb40aa3604))
* added 'as' prop to the validation provider ([5c8ae9c](https://github.com/logaretm/vee-validate/commit/5c8ae9cac2dd418c5bf78b8a0c68e7d256dc96ce))
* added alert role to the error message ([714abfe](https://github.com/logaretm/vee-validate/commit/714abfede6cb2cd2ab1dd72319d27630af6fe9b6))
* added aria and a11y improvements ([ca74f16](https://github.com/logaretm/vee-validate/commit/ca74f165988be3c0c5a6f828508b6aed3fd6e3a0))
* added built-in support for yup validation schema ([e436b75](https://github.com/logaretm/vee-validate/commit/e436b75c4b8b7a085adf701d07b54b798da9a774))
* added ErrorMessage component ([9570412](https://github.com/logaretm/vee-validate/commit/957041270b947e1b70301c3935b6d1ac0bb05a5d))
* added support for custom components ([c661c7e](https://github.com/logaretm/vee-validate/commit/c661c7e1f352e2806c2e2da7bc2c860cfa62f3ff))
* added useField and useForm hooks ([c1e9007](https://github.com/logaretm/vee-validate/commit/c1e900736ed9585d8997d2080f001aad28060281))
* allow the as prop to be a component definition ([29790d4](https://github.com/logaretm/vee-validate/commit/29790d47f17fe49c897bf5b2fda0508f57990479))
* allow the observer to render forms and handle submit events ([9e0d59b](https://github.com/logaretm/vee-validate/commit/9e0d59b11d239c7f1e6d4bc287d9e49aa0376f0d))
* allow validation schema to accept other expressions ([ddeeaea](https://github.com/logaretm/vee-validate/commit/ddeeaea8041c3fad894aff0c827dd9f71b65224d))
* change default field value to undefiend ([00c8754](https://github.com/logaretm/vee-validate/commit/00c87549244447423e0833f8294c5c607bdcf105))
* deprecate names option on validate API ([fe90820](https://github.com/logaretm/vee-validate/commit/fe90820b4b0d4d10df81c2bbd019c3b63d371edf))
* deprecate the 'required' flag ([283caa0](https://github.com/logaretm/vee-validate/commit/283caa0fdd353d990680d42e64be8d8362b6aad5))
* enable interaction modes and localization APIs ([8486aaf](https://github.com/logaretm/vee-validate/commit/8486aaf0fadba03f38b5dd8a5ab857c10e7aa49c))
* expose errorMessage prop on useField and Provider ([04eecaa](https://github.com/logaretm/vee-validate/commit/04eecaa13cc8ab0cc18336021bb912f924e37968))
* expose the form values and pass them to the handleSubmit ([de51155](https://github.com/logaretm/vee-validate/commit/de511555c371bef73037d514e19d44eb4d292eae))
* hook up the provider with new observer implementation ([4d18a65](https://github.com/logaretm/vee-validate/commit/4d18a6572af6af4630bdc2508e027e67d3c0d579))
* implement bails for useField and ValidationProvider ([486babd](https://github.com/logaretm/vee-validate/commit/486babd031efd5a71a819ff535a0e0c661bc45fe))
* implement initial values ([8239130](https://github.com/logaretm/vee-validate/commit/82391301152751eb03097dad4521dc1c275c47e7))
* implement validation debounce ([e294409](https://github.com/logaretm/vee-validate/commit/e2944099ef2074d59f908f7949df3a1059ab3b4e))
* implemented disabled prop ([88bf28e](https://github.com/logaretm/vee-validate/commit/88bf28e89d9e635ebbc79e593a326d4dd2025cdb))
* make rules watchable ([90530cd](https://github.com/logaretm/vee-validate/commit/90530cdebede5bf33a62221371380ad8554326ba))
* make the as prop take priority to determine what to render ([d5a033f](https://github.com/logaretm/vee-validate/commit/d5a033fc57b7ddea8aff4a0f4fe802d7c2489a9c))
* new field binding object ([a58a84b](https://github.com/logaretm/vee-validate/commit/a58a84b009fef5dbfffa2a93a54643b3830cb4bc))
* new handleSubmit signature ([63cbeaf](https://github.com/logaretm/vee-validate/commit/63cbeafd1cfb5e1e14ec42e34c0691a26b258897))
* only export the provider for now ([0bf3efe](https://github.com/logaretm/vee-validate/commit/0bf3efe230be2d80b9e4693779e095c04997a52b))
* remove vid from fields ([1b9bded](https://github.com/logaretm/vee-validate/commit/1b9bdedeb68006535c7087aef267906e2f7bed1d))
* support immediate validation ([42cd6ed](https://github.com/logaretm/vee-validate/commit/42cd6edcfc0c11ea05106e66486ed4772c749548))
* support inline rules as functions ([3c74681](https://github.com/logaretm/vee-validate/commit/3c7468186ac5a6e7fa6bb44b30de4102ef5c31cd))
* support yup validation schemas on field-level ([0802512](https://github.com/logaretm/vee-validate/commit/0802512e181a8a33feaa227770f9e203fcf0cea5))
* updated vnode utils to handle Vue 3 VNode API ([29a4fe8](https://github.com/logaretm/vee-validate/commit/29a4fe859823d5a74814c2dabb3b664185e56366))
* use defineComponent to type Provider and Observer definitions ([80980cf](https://github.com/logaretm/vee-validate/commit/80980cfec81447638aa82b42c208f9ec6f9826f8))
* validate yup form schemas using object validation ([bf216dd](https://github.com/logaretm/vee-validate/commit/bf216dde30a6d90c976bac844129ccbd08a00392))
* validation schema support ([523824a](https://github.com/logaretm/vee-validate/commit/523824a0977d599f6ff2a271ee2edebd5aef36ef))
* working draft for the vprovider with composition api ([b830054](https://github.com/logaretm/vee-validate/commit/b8300547cbafa9904f2b769b8309925ad6da180f))