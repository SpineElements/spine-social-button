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
`--spine-social-button-disabled` | Mixin passed to the `--paper-button-disabled` mixin| `{}`
`--spine-social-button-focus` | Mixin passed to the `--paper-button-raised-keyboard-focus` mixin | `{}`

The list of default background colors for supported providers:

Provider name | Color   | Source
--------------|---------|---------
Google        | #3367d6 | paper-styles/color.html: `--google-blue-700`
Github        | #333    | http://primercss.io/colors/
Facebook      | #3b5998 | https://brandcolors.net/b/facebook
Twitter       | #1da1f2 | https://brand.twitter.com/logo
