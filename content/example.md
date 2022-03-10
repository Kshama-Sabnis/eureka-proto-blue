---
layout: blog.11ty.js
title: Blog Title
description: Blog Description. Note: This will be used for SEO!
hero: https://images.unsplash.com/photo-1497443505411-625700fc83c3?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2000
heroCropMode: bottom
heroColor: dark
---

The section right above (between the ---'s) is called the Front Matter. The Front Matter contains metadata that will be processed by the site generation pipeline. For example, heroCropMode determines whether the site will choose to render the "top", "center", or "bottom" of the hero image. 

heroColor can be "light" or "dark" and should describe the general color of the hero image. For dark images, we will use white text, for light images, we will use black text. 

When selecting a hero image, you can use a site like https://unsplash.com/. Try to avoid images that are too busy with too many color transitions, as these will not serve as good backgrounds for mono-colored text. 

Markdown Cheat Sheet: https://www.markdownguide.org/basic-syntax/

## Relational
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer eget dolor eros. Quisque ac quam vestibulum, venenatis nibh blandit, laoreet ante. Vestibulum vel tempor dolor. Vivamus velit lacus, dignissim sit amet tincidunt vel, pulvinar quis risus. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Mauris dignissim sapien lacus, a pulvinar arcu viverra ut. Fusce tempus ultrices elit, id aliquam erat aliquet ac. Aenean posuere efficitur ipsum, nec auctor nisl ullamcorper vitae. Duis feugiat vehicula diam, eu dictum enim varius quis. Aenean blandit non nibh nec auctor. Aenean lacinia tortor id augue maximus, vitae egestas orci hendrerit. Morbi tincidunt laoreet erat, vitae efficitur eros rutrum ac. Fusce quis suscipit massa, vehicula consequat tortor. Pellentesque volutpat neque diam, pellentesque pretium risus posuere sed. Vivamus dictum non ipsum vel cursus. Etiam ac lectus in risus convallis gravida.

```JavaScript
DynamoDbClient client = DynamoDbClient.builder()
    .endpointOverride(URI.create("http://localhost:8000"))
    // The region is meaningless for local DynamoDb but required for client builder validation
    .region(Region.US_EAST_1)
    .credentialsProvider(StaticCredentialsProvider.create(
    AwsBasicCredentials.create("dummy-key", "dummy-secret")))
    .build();
```

## Key-Value
Nunc ac consequat velit, ac viverra mauris. Nunc lacinia diam tristique eros suscipit ultricies. Pellentesque sollicitudin lacus in tellus auctor blandit. Vestibulum nec interdum turpis. Morbi eget turpis ac lacus efficitur scelerisque. Aliquam ullamcorper cursus leo, quis fringilla quam vulputate vitae. Aenean aliquam, mi eu scelerisque vulputate, nisi sapien semper arcu, nec vestibulum ligula diam eget ante. Pellentesque interdum faucibus nulla, et finibus ligula. Ut commodo, lacus at lobortis hendrerit, risus leo lacinia velit, eget vulputate arcu nunc a leo. Nunc molestie metus eu fermentum pulvinar. Praesent nec pulvinar erat, vitae condimentum eros. Ut accumsan non urna et placerat. Morbi viverra dui nec turpis fermentum posuere. Curabitur ut luctus eros. Praesent laoreet blandit dolor sit amet rutrum. Aenean non neque non ligula suscipit viverra et id lorem.

```Java
import com.amazonaws.services.dynamodbv2.AmazonDynamoDBClientBuilder;
import com.amazonaws.regions.Regions;
...
// This client will default to US West (Oregon)
AmazonDynamoDB client = AmazonDynamoDBClientBuilder.standard()
.withRegion(Regions.US_WEST_2)
.build();  
```

## Key-Document
Vestibulum at mi quis purus facilisis condimentum. Praesent molestie leo quis purus sollicitudin, non aliquam arcu hendrerit. Suspendisse quis aliquam arcu. Morbi quis ullamcorper dolor, efficitur finibus est. In odio purus, dictum ac sem ut, consequat sollicitudin libero. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec id imperdiet augue. 

- Pellentesque interdum aliquet mauris vestibulum tempus. Morbi dignissim, dolor ut tincidunt lacinia, tellus est fermentum nibh, ac pharetra lectus neque vel tortor. 
- Cras enim nibh, tristique eget urna ac, pretium varius elit. Vestibulum erat nulla, condimentum sed gravida eget, sollicitudin et elit. 
- In scelerisque neque sit amet mauris convallis varius. Donec eleifend felis eu pellentesque pretium. 
- Donec pharetra risus libero, vitae mollis nisl maximus eget. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.

## Graph
Ut ac urna justo. Fusce quis tempor arcu, et luctus nisl. Maecenas ac massa condimentum, fermentum erat sed, blandit eros. Sed maximus viverra facilisis. Aenean rhoncus non mi non consequat. Pellentesque maximus dui quis turpis tincidunt, ut tristique urna varius. Phasellus hendrerit leo justo, sit amet sagittis dolor tempus a.

![Tux, the Linux mascot](https://miro.medium.com/max/1200/1*Xw7DCLDx49q1k14duZmxEQ.png)

## Time-Series
Vestibulum non egestas dui. Cras id vulputate mi. Donec cursus, justo ullamcorper ultricies malesuada, quam tortor fermentum nunc, non porttitor nisi erat ornare metus. Sed eu viverra odio. Integer sit amet pharetra sapien, eget gravida nisl. In molestie nunc a enim scelerisque tristique. In varius neque urna, vitae tempor enim dignissim ac. Donec tincidunt purus lorem. Aenean et vehicula nulla. Nulla vel mi nunc. Maecenas tempus eleifend ex sit amet commodo. Aenean sagittis molestie quam, nec tempor quam. Vivamus ullamcorper, ipsum sit amet feugiat lacinia, libero velit euismod odio, eget vestibulum ligula urna sollicitudin felis. Aliquam accumsan, ante sit amet euismod posuere, nunc justo feugiat nisl, in faucibus turpis velit iaculis elit. Nunc ac lorem eu lorem posuere dignissim. Donec fermentum lacus et neque aliquet lobortis.

