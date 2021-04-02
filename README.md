## Super Human Humor with GPT2

I scraped all [r/jokes](https://www.reddit.com/r/Jokes/) from 2017 to 2020 with more than 5 upvotes with https://pushshift.io/ and combined them with the existing data set from https://github.com/taivop/joke-dataset.

Then, I loaded GPT2 with huggingface's transformers library and fine-tuned it on the jokes with pytorch.
The notebook is adapted from this [blog post](https://medium.com/swlh/fine-tuning-gpt-2-for-magic-the-gathering-flavour-text-generation-3bafd0f9bb93).

### Examples

As [r/jokes](https://www.reddit.com/r/Jokes/) enjoys dark humor, don't take the outputs too seriously!

```
Why do Sumo wrestlers shave their legs in between their sets?
Because Sumo wrestlers have a great ass.
```


```
My wife asked me which shampoo I should apply.
So I just gave her 3 different. Guess I should try Tide Pods or something...
```


```
Wife's: It feels like you are having a heart attack

Husband: Oh well.

Wife's: (unfazed) I have a headache...

Husband: But I'm still having a headache.

Wife's: Is it your wife?

Husband: (laughing) Sorry.
```

```
My son is such an insufferable cunt I even tried to have him vaccinated against measles and polio.
But boy, is it still possible to have a kid without autism?
```

```
I was on a blind date with this girl the other day.
We clicked because she wasn't wearing any clothes. 
```

One could argue that my model really only produces nonsense.
But I firmly believe that it simply transcended human humor.
So why should we understand its jokes?!
