# CleanMVVPArchitecture
Model View View-Model is introduced in last year’s Google I/O.This architectural plan is becoming popular by the features it provides. It mainly implements the Data Binding Framework, it allows for “binding” of views to fields on an arbitrary object. When a field is updated, the framework is notified and the view is updated automatically. The architecture introduces two-way communication between its components. Along with features like binding, Automatically updating views, it also easy for testing purpose.The functionality of Model and View is same as we have discussed in MVP. - See more at: http://www.tothenew.com/blog/androidmvc-mvp-mvvm/#sthash.n1wTebu0.dpuf

# View-Model
It is responsible for exposing methods, commands, and other properties that helps to maintain the state of the view, manipulate the model as the result of actions on the view, and trigger events in the view itself.View has a reference to View-Model but View-Model has no information about the View.There is many-to-one relationship between View and View-Model means many View can be mapped to one View-Model. It is completely independent of Views. - See more at: http://www.tothenew.com/blog/androidmvc-mvp-mvvm/#sthash.n1wTebu0.dpuf

# Moel
Model here too plays role of domain or business layer and is data source of pattern. It describe the main logic of application and decides from where the data should be fetched. - See more at: http://www.tothenew.com/blog/androidmvc-mvp-mvvm/#sthash.n1wTebu0.dpuf

# View
It renders information to users and contains UI Component .Xml file, Activity, fragments, Dialog comes under View Layer.It do not have any other logic implemented. - See more at: http://www.tothenew.com/blog/androidmvc-mvp-mvvm/#sthash.n1wTebu0.dpuf

