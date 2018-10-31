# React Bulma Steps

A component based on https://aramvisser.github.io/bulma-steps/.  The component uses the new ContextAPI and requires a version of react compatible with it.

## [DEMO](https://tml123.github.io/react-bulma-steps)

## To use:

A distribution is not available, but feel free to grab the src, contribute, suggest, etc.

Eventually, some content having to do with usage to go here....but something like this:

```
<Steps dashed={true} activeStep={`step${this.state.activeStep}`}>
    <Step id={'step1'} marker={1} details={`Some details for step 1`}></Step>
    <Step id={'step2'} marker={2} details={`Some details for step 2`}></Step>
    <Step id={'step3'} marker={3} details={`Some details for step 3`}></Step>
    <Step id={'step4'} marker={4} details={`Some details for step 4`}></Step>
    <Step id={'step5'} marker={5} details={`Some details for step 5`}></Step>
</Steps>
```