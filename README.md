The clock in the app is from the Unity ['Introduction to Lifecycle Methods](https://www.codecademy.com/paths/full-stack-engineer-career-path/tracks/fscp-react-part-ii/modules/fecp-lifecycle-methods/lessons/component-lifecycle-methods/exercises/introduction-to-lifecycle-methods).

The time is loaded when the app renders but it doesn't update. The question is where exactly to put exactly the updating function.

const oneSecond = 1000;
setInternal(() => {
this.setState({date : new Date});
}, oneSecond)
