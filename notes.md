# Edit, Show and Delete Buttons

<div class="post-btns">
        <!-- <%= link_to 'Show', post %> -->
        <div><a href="/posts/<%= post.id %>"><i class="fas fa-book-reader"></i></a></div>
        <!-- <%= link_to 'Edit', edit_post_path(post) %> -->
        <div><a href="/posts/<%= post.id %>/edit"><i class="far fa-edit"></i></a></div>
        <!-- <%= link_to 'Destroy', post, method: :delete, data: { confirm: 'Are you sure?' } %> -->
        <div><a data-confirm="Are you sure?" rel="nofollow" data-method="delete" href="/posts/<%= post.id %>"><i class="far fa-trash-alt"></i></a></div>
      </div>