# States

It is important for you to know the states in which the lists and entry points can be found.

### Entry points

**DRAFT**. The state an entry point is in when you first create it and save your changes before publishing it.

**PUBLISHED**. The user will see the entry point as long as it is configured for an audience that includes the user and within a list that is also published.

{% hint style = "warning" %} Remember that entry points can be found in different lists, and that to be seen it has to be published. However, the fact that the entry point is in **PUBLISHED** state does not mean that it will be seen. This will depend on the state of the list(s) that contain it and the audiences configured in those lists. {% endhint %}

**PAUSED**. Unpublished state. The entry point has been published at some point but it is no longer published. It cannot be viewed by any user.

**TEST**. A test is ongoing for the entry point.

:nerd: For more information about how a test behaves in an entry point, see the section [Test on an entrypoint](como-hacer-un-test.md#test-sobre-un-entrypoint).

Here is a small diagram which depicts how you can transition from one state to another.

![Cómo transiciona un entrypoint de un estado a otro en función del estado de inicio ](https://github.com/nazaretcaballo-CX/entrypoints-CMS/blob/ES/en-US/.gitbook/assets/Estados_entrypoint.png?raw=true)

### Lists

**DRAFT**. The state a list is in when you first create it and save your changes before publishing it.

**PUBLISHED**. The user will see the list and the corresponding entry points according to the configured audiences.

**PAUSED**. Unpublished state. The list has been published at some point but it is no longer published. It cannot be viewed by any user.

**TEST**. The list may have a test in progress. This state is always combined with:

- **PAUSED + TEST**. In this case, the list is undergoing a test. While the test is ongoing, the users will not see it. Only those who are configured for the test will be able to see it.
- **PUBLISHED + TEST**. In this case, the list is undergoing a test but remains published for the rest of the users. The users of the test will see the test version of the list, and the rest of the users will see the list as it was in the beginning (in the published version).

Here is a small diagram showing how you can move from one state to another.

![Cómo transiciona una lista de un estado a otro en función del estado de inicio](https://github.com/nazaretcaballo-CX/entrypoints-CMS/blob/ES/en-US/.gitbook/assets/Estados_listas.png?raw=true)
