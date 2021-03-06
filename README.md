# Awesome Promise Cancellation

Some resources to read about the cancellation/cancelation of Promises.

## Specification proposals / Related Implementations

| Title | Link | Highlights |
|---|---|---|
| Promise A-Plus Cancellation Spec | https://github.com/promises-aplus/cancellation-spec/issues |
| Cancelable Promise | https://github.com/domenic/cancelable-promise | [Third State](https://github.com/domenic/cancelable-promise/blob/master/Third%20State.md) |
| Bluebird Cancellation API | http://bluebirdjs.com/docs/api/cancellation.html |
| ES Cancel Token | https://github.com/zenparsing/es-cancel-token | [thirdState integration](https://github.com/zenparsing/es-cancel-token/issues/4) |

## Discussions

### Starting points

| | |
|---|---|
| Cancelling HTTP fetch | https://github.com/slightlyoff/ServiceWorker/issues/592 |
| Aborting a fetch | https://github.com/whatwg/fetch/issues/27 |
| ES Discuss - Cancelable Promises | https://esdiscuss.org/topic/cancelable-promises |

### Cancelable-Promise

| | |
|---|---|
| Is throw cancel necessary? | https://github.com/domenic/cancelable-promise/issues/10 |
| How async functions play with cancellation | https://github.com/domenic/cancelable-promise/issues/7 |
| Potential Security issue when applied to fetch | https://github.com/domenic/cancelable-promise/issues/4 |

and of course all other issues as well - https://github.com/domenic/cancelable-promise/issues

### Bluebird

| Title | Link | Highlights |
|---|---|---|
| Cancellation API docs | http://bluebirdjs.com/docs/api/cancellation.html |
| Promise.cancel() | https://github.com/petkaantonov/bluebird/issues/554 |
| 3.0 Cancellation overhaul | https://github.com/petkaantonov/bluebird/issues/415 | [summary](https://github.com/petkaantonov/bluebird/issues/415#issuecomment-88057439) |
| Don't use a third cancelled state | https://github.com/petkaantonov/bluebird/issues/565 | [strategies](https://github.com/petkaantonov/bluebird/issues/565#issuecomment-90760540) |

## Slides

| | |
|----|----|
| Investigations and a proposed direction | https://docs.google.com/presentation/d/1V4vmC54gJkwAss1nfEt9ywc-QOVOfleRxD5qtpMpc8U |

## Videos

| | |
| --- | --- |
| Debate about Promise Cancellation with [@blesh](https://github.com/blesh) & [@samccone](https://github.com/samccone) | https://www.youtube.com/watch?v=65-WwVfAcl8 |
