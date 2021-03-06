# \<spine-ssocial-button\>

`spine-social-button` is a [<paper-button>](https://www.webcomponents.org/element/PolymerElements/paper-button)
styled with an icon which represents a certain social domain (e.g. Google, Github, Facebook).

Example:
```
  <spine-social-button provider="google">Sign up with Google</spine-social-button>
  <spine-social-button provider="github">Sign up with Github</spine-social-button>
  <spine-social-button provider="facebook">Sign up with Facebook</spine-social-button>
  <spine-social-button provider="twitter">Sign up with Twitter</spine-social-button>

  <spine-social-button provider="google" icon="my-icons:google">Sign in with Google</spine-social-button>

  <spine-social-button icon="spine-social-button:google">Share</spine-social-button>
  <spine-social-button icon="my-icons:twitter">Share</spine-social-button>
```

The following custom properties and mixins are available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--spine-social-button-background` | Background color of the button | specified according to `provider`
`--spine-social-button` | Mixin applied to the <paper-button> | `{}`
`--spine-social-button-disabled` | Mixin passed to the `--paper-button-disabled` mixin | `{}`
`--spine-social-button-keyboard-focus` | Mixin passed to the `--paper-button-raised-keyboard-focus` mixin | `{}`

The default styling when `provider` property is specified:

Provider property | background-color   | icon
------------------|--------------------|------------------------------
google            | #3367d6            | spine-social-button:google
github            | #333               | spine-social-button:github
facebook          | #3b5998            | spine-social-button:facebook
twitter           | #1da1f2            | spine-social-button:twitter
