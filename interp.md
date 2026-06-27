One of the key values of interpretability tools is they aid in human oversight by enabling open ended evaluations. When treating the models as black boxes it becomes increasingly difficult to attribute different aspects of biases, deception and overfitting that the model experiences. In an era where agentic systems will be doing most of the tasks the surface area grows exponentially for deceptive behaviour to emerge as agents get more smarter so does there ability to display increased level of threat. 

Little development history of interpretability

 Distill in 2017,
2022 surge in interpretability tools 
STARTING OF ARC
Redwood research and its remix programme
5199 papers on interpretability 

It is important to have theoretical frameworks as works as well as actionable tools that help to deploy these research solutions into business environments 


Introduction to interpretability 

Any method of evaluating a model is only a proxy for its actual performance. The most common way most of these ai systems are being tested is by using the evaluation frame works which is very important by they make us incentivize and move us in the direction of creating correlations and hypothesis that are deceptive, biased and have potential to reach conclusion which are subpar. 

When should we use interpretability ?

The right tool in the wrong hands can be nothing but dead weight. Especially when it comes to the case of interpretability it is important to be particularly careful about this. If you look at interpretability from an end use perspective the amount of resources spent to the change that you witness can be further deceiving and push you more towards being more skeptical about interpretability. Yet so it is most forms of science it important to be much more critical about ideas but also we should not be dismissive of ideas. In the far future when we are close something of a super intelligence it is absolutely important to grasp every aspect of its memory trace even a tiny hint of bias, values that are antithesis to human moral can be detrimental and can compound in every iteration of model generations so diverting resources which is our most probable bet of probing inside the minds of ai should not be ignored. 


If you look at interpretability from an engineers lens it would a slight be impractical atleast for now but given enough time and iterations of models I believe it is worth spending time  and resources on.

Interpretability refers to the line of methods that attempts to interpret or simply reverse  engineer the underlying architectural patterns, activations connections in a human understandable mechanisms is called interpretability. These techniques can help us probe change and mitigate risks due to these internals. Although there are several techniques for supervised models which we will cover in (write the section number and link) we are exclusively focused on generative models here for now. Here i tried to put together all the diverse techniques, explanations for ml techniques and future research directions for references as this work is open draft I am looking to add more content along the way. 

We cover various topics like feature study, circuit study, university of them, work each category of the actionable task workflows. I intend to also include techniques for engineers like knowledge editing lm steering etc. 



Point to the appendix sections with the following 


Different promising and used architectures of the various models and stuff about them like attention mechanism, weights, etc etc 

Hard code a small model using karpathys gpt2 or similar from scratch for programming people 

Point to resources from 3 b1b about transformers 

Make animations about the architecture // 
 



Mechanistic interpretability if a field of interpretability which primarily focuses on reverse engineering the model internals. 

Features 
A feature is a human interperetable input property 

Feature dog -> animal, pet four legs, loyal etc and other features learned during the pretraining embedding these features into the lm 

Circuits 

features helps us understand what information is being encoded in models activations. It does not helps us understand how these are extracted from the inputs. Circuits helps us understand these by connecting features with specific lm behaviours. 

Features -> nodes and weighted connections between them as edges as circuits 

Where interpreting individual transformers components becomes part of circuit interpretation. 



Circuit definition both normal and format and animations would be added here 

Universality 
The concept of universality is central to the mechanistic interpretability when we are comparing across different language models if a particular set of features or circuits form an internal structure and if these structures are transferable to different models then implications are huge. We can painstakingly probe a neural architecture which is small and transfer it to much larger models where studying these can be challenging. If there are no guarantee of universality it becomes very hard to study the effects even when the task at hand is changed, dealing with an inter connected task or even same architectural model with a different training run. 



Feature study can be done via two different methods 

What information is encoded in the model internals 

Look for something
→ make a hypothesis 
→ very a hypothesis 
Open ended feature discovery  
→ observe 
→ explain 


Moving onto the circuit study 

→ trace the flow of information through the ,model components 

How do we compute a specific behaviour ? 

Flow of information through the model components 

→ starting with a behavior 
Step 1 choose a behaviour 
Step 2 define the computational graph 
Step 3 localization 
Step 4 Explaining the circuit analysis 

→ starting with an component 
Step 1 choose a component 
Step 2 explain circuit analysis 
Step 3 identify patterns 
Step 4 study the emergent behaviour 

Universality study 

Are the features and behaviours transferable 

Step 1 define the scope of the study 
→ Universality of features
→ universality of circuits
Step 2 Dimensions of variations 
→ across different lm 
→ across different tasks 
Step 3 Feature or circuit study 

Different interpretability techniques that does not require looking inside the black box models include lime, shap, integrated gradients, 

These can help you identify relations between the input and the outputs like which pixel can help you get the results that you are looking for they do not provide insight into what might have caused it 


Other probing techniques in mechanistic interpretability that also probes the internals 

Probing classifiers and attention weight analysis 

Mechanistic interpretability can be classified into two different approaches 

Top down and bottom up approaches 


Bottom up approach 
Breaking down all the model elements into small components and gradually piece them together to produce complex model behaviour 

Top down approach 

Top down approach looks and identifies units of layers or modules and move down from it trying to piece together how 



