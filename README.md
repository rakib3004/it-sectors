
## Company List

```json
[
{"name": "BJIT", "facebook": "bjitltd", "linkedin": "bjit", "email": "digital.marketing@bjitgroup.com"},
{"name": "Bkash", "facebook": "bkashlimited", "linkedin": "bkash-limited", "email": "hr@bkash.com"},
{"name": "Brac IT", "facebook": "bracits", "linkedin": "bracits", "email": "support@braincraftapps.com"},
{"name": "Brain Craft", "facebook": "BrainCraftLtd", "linkedin": "brain-craft-ltd", "email": "support@braincraftapps.com"},
{"name": "Brain Station 23", "facebook": "brainstation23", "linkedin": "brain-station-23-plc", "email": "sales@brainstation-23.com"},
{"name": "Cefalo", "facebook": "cefalobangladesh", "linkedin": "cefalobangladesh", "email": "contact@cefalo.com"},
{"name": "DSI", "facebook": "DynamicSolutionInnovators", "linkedin": "dsinnovators", "email": "info@dsinnovators.com"},
{"name": "Enosis", "facebook": "EnosisSolutions", "linkedin": "enosis-solutions", "email": "info@enosisbd.com"},
{"name": "Infolytx", "facebook": "Infolytx", "linkedin": "infolytx-inc", "email": "inquiry@infolytx.com"},
{"name": "IQVIA", "facebook": "IQVIA", "linkedin": "iqvia", "email": "contact@iqvia.com"},
{"name": "Kona", "facebook": "KonaSL", "linkedin": "konasl", "email": "info_ksl@konasl.com"},
{"name": "Optimizely", "facebook": "optimizely", "linkedin": "optimizely", "email": "support@optimizely.com"},
{"name": "Orbitax", "facebook": "OrbitaxBangladesh", "linkedin": "", "email": "info@orbitax.com"},
{"name": "Reve", "facebook": "REVESystems", "linkedin": "reve-systems", "email": "info@revesoft.com"},
{"name": "Samsung", "facebook": "samsungsrbd", "linkedin": "samsaungsrbd", "email": "recruitment.srbd@samsung.com"},
{"name": "Selise", "facebook": "selisebangladesh", "linkedin": "selise", "email": "support@selise.ch"},
{"name": "Streams Tech", "facebook": "streamstech", "linkedin": "streamstech", "email": "contact@streamstech.com"},
{"name": "Therap", "facebook": "TherapBD", "linkedin": "therapbd", "email": "info@therapbd.com"},
{"name": "Tiger IT", "facebook": "tigerit", "linkedin": "tigerit-bangladesh-limited", "email": "info@tigerit.com"},
{"name": "Vivasoft", "facebook": "vivasoftltd", "linkedin": "vivasoftltd", "email": "biz.dev@vivasoftltd.com"},
{"name": "WellDev", "facebook": "Welldev", "linkedin": "welldevintl", "email": "contact@welldev.io"},
]
```


## Keep React Library Code

```javascript

"use client";
import { Heart } from "phosphor-react";
import { Avatar, Card } from "keep-react";

export const CardComponent = () => {
  return (
    <Card
      imgSrc="https://images.prismic.io/staticmania/821cee7b-6b44-48c4-ab95-8a525056489d_blog.jpg?auto=compress,format"
      imgSize="md"
      className="max-w-xs">
      <Card.Container className="absolute right-3.5 top-3.5 flex h-10 w-10 cursor-pointer items-center justify-center rounded-full bg-metal-200">
        <Heart size={20} weight="bold" color="white" />
      </Card.Container>
      <Card.Container className="flex flex-col items-center justify-center">
        <Card.Container className="absolute top-32  rounded-full ring-4 ring-white ring-offset-0">
          <Avatar size="2xl" shape="circle" img="/images/avatar/avatar-4.png" />
        </Card.Container>
        <Card.Container className="mb-3 mt-10 text-center">
          <Card.Title className="text-body-5 font-semibold text-metal-800 md:text-body-4">Khairul Islam</Card.Title>
          <Card.Title className="!text-body-6 font-normal text-metal-400 md:text-body-5">UI/UX Designer</Card.Title>
        </Card.Container>
        <Card.Container className="flex w-full justify-between border-t border-t-metal-50 px-5 py-3">
          <Card.Container className="text-center">
            <Card.Title className="text-body-5 !font-normal text-metal-400 md:text-body-5 md:!font-medium">
              Post
            </Card.Title>
            <Card.Title className="!text-body-1 !font-semibold text-metal-800">254</Card.Title>
          </Card.Container>
          <Card.Container className="text-center">
            <Card.Title className="text-body-5 !font-normal text-metal-400 md:text-body-5 md:!font-medium">
              Followers
            </Card.Title>
            <Card.Title className="!text-body-1 !font-semibold text-metal-800">1245M</Card.Title>
          </Card.Container>
          <Card.Container className="text-center">
            <Card.Title className="text-body-5 !font-normal text-metal-400 md:text-body-5 md:!font-medium">
              Following
            </Card.Title>
            <Card.Title className="!text-body-1 !font-semibold text-metal-800">58</Card.Title>
          </Card.Container>
        </Card.Container>
      </Card.Container>
    </Card>
  )
}

```