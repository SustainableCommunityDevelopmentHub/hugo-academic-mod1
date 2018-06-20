---
title: Documents
author: admin
type: page
date: 2018-04-13T15:47:54+00:00

---
<div class="mdocs-donate-btn">
</div>

<div class="mdocs-wrap">
  <div class="mdocs-admin-preview">
  </div>
  
  <h2>
    Documents Library
  </h2>
  
  <div class="btn-group" role="group">
    <button class="add-update-btn btn btn-danger" data-toggle="modal" data-target="#mdocs-add-update" data-mdocs-id="" data-is-admin="1" data-action-type="add-doc"  data-current-cat="mdocuments" href=""><i class="fa fa-upload fa-lg" aria-hidden="true"></i> Add New Document</button> <button class="btn btn-default" onclick="mdocs_batch_edit()" data-toggle="mdocs-modal" data-target="#mdocs-batch-edit"><i class="fa fa-pencil" aria-hidden="true"></i> Batch Edit</button> <button class="btn btn-default" onclick="mdocs_batch_move()" data-toggle="mdocs-modal" data-target="#mdocs-batch-move"><i class="fa fa-refresh" aria-hidden="true"></i> Batch Move</button> <button class="btn btn-default" onclick="mdocs_batch_delete()" data-toggle="mdocs-modal" data-target="#mdocs-batch-delete"><i class="fa fa-trash" aria-hidden="true"></i> Batch Delete</button> 
    
    <div class="btn-group" role="group">
      <button class="btn btn-default dropdown-toggle" type="button" id="dropdownMenu1" data-toggle="dropdown"><i class="fa fa-wrench" aria-hidden="true"></i> Options <i class="fa fa-caret-down" aria-hidden="true"></i></button> 
      
      <ul class="mdocs-dropdown-menu" role="menu" aria-labelledby="dropdownMenu1">
        <li role="presentation" class="dropdown-header">
          File Options
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=cats">Edit Folders</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=allowed-file-types">Allowed File Types</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=import">Import</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=export">Export</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=batch">Batch Upload</a>
        </li>
        <li role="presentation" class="divider">
        </li>
        <li role="presentation" class="dropdown-header">
          Admin Options
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=settings">Settings</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=find-lost-files">Find Lost Files</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=filesystem-cleanup">File System Cleanup</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=restore">Restore To Default</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=short-codes">Short Codes</a>
        </li>
        <li role="presentation">
          <a role="menuitem" tabindex="-1" href="?page=memphis-documents.php&mdocs-cat=server-compatibility">Test Server Compatibility</a>
        </li>
      </ul>
    </div>
  </div>
  
  <br /><br /> 
  
  <div class="mdoc-navbar-container">
    <nav class="navbar mdocs-navbar-default" role="navigation" id="mdocs-navbar"> 
    
    <div class="container-fluid">
      <div class="navbar-header">
        <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#mdocs-navbar-collapse"> <span class="sr-only">Toggle navigation</span> <span class="icon-bar"></span> <span class="icon-bar"></span> <span class="icon-bar"></span> </button> <span class="navbar-brand">Folders</span>
      </div>
      
      <div class="collapse navbar-collapse" id="mdocs-navbar-collapse">
        <ul class="nav navbar-nav">
          <li>
            <a href="?page=memphis-documents.php&mdocs-cat=mdocuments ">Documents</a>
          </li>
        </ul>
      </div>
    </div></nav>
  </div>
</div>

<div class="mdocs-container">
  <table class="table table-hover table-condensed" id="mdocs-list-table">
    <tr class="hidden-sm hidden-xs">
      <th id="batch">
        <input type="checkbox" name="mdocs-batch-select-all" id="mdocs-batch-select-all" />
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="name" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Name
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="downloads" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Downloads
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="modified" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Last Modified <i class="fa fa-chevron-down" aria-hidden="true"></i>
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="rating" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Rating
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="download" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Download
      </th>
    </tr>
    
    <tr class="hidden-sm hidden-xs">
      <th id="batch">
        <input type="checkbox" name="mdocs-batch-select-all" id="mdocs-batch-select-all" />
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="name" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Name
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="downloads" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Downloads
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="modified" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Last Modified <i class="fa fa-chevron-down" aria-hidden="true"></i>
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="rating" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Rating
      </th>
      
      <th class="mdocs-sort-option" data-disable-user-sort="" data-sort-type="download" data-current-cat="mdocuments" data-permalink="admin.php?page=memphis-documents.php&mdocs-cat=mdocuments&mdocs-att=none">
        Download
      </th>
    </tr>
    
    <tr class="mdocs-current-cat" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        <i class="fa fa fa-folder-open-o" aria-hidden="true"></i> Documents
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-5&mdocs-att=null" title="Climate"><i class="fa fa-folder-o" aria-hidden="true"></i> Climate</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-13&mdocs-att=null" title="Education"><i class="fa fa-folder-o" aria-hidden="true"></i> Education</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-1&mdocs-att=null" title="Energy"><i class="fa fa-folder-o" aria-hidden="true"></i> Energy</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-2&mdocs-att=null" title="Engineering"><i class="fa fa-folder-o" aria-hidden="true"></i> Engineering</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-11&mdocs-att=null" title="Food"><i class="fa fa-folder-o" aria-hidden="true"></i> Food</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-3&mdocs-att=null" title="Health"><i class="fa fa-folder-o" aria-hidden="true"></i> Health</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-10&mdocs-att=null" title="Land Management"><i class="fa fa-folder-o" aria-hidden="true"></i> Land Management</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-12&mdocs-att=null" title="Shelter"><i class="fa fa-folder-o" aria-hidden="true"></i> Shelter</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-9&mdocs-att=null" title="Social Enterprise"><i class="fa fa-folder-o" aria-hidden="true"></i> Social Enterprise</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-8&mdocs-att=null" title="Transportation"><i class="fa fa-folder-o" aria-hidden="true"></i> Transportation</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-7&mdocs-att=null" title="Waste Management"><i class="fa fa-folder-o" aria-hidden="true"></i> Waste Management</a>
      </td>
    </tr>
    
    <tr class="mdocs-sub-cats" >
      <td colspan="6" id="title" class="mdocs-tooltip">
        &emsp;&emsp;<a href="admin.php?page=memphis-documents.php&mdocs-cat=mdocs-cat-6&mdocs-att=null" title="Water"><i class="fa fa-folder-o" aria-hidden="true"></i> Water</a>
      </td>
    </tr>
    
    <tr>
      <td colspan="10">
        <p class="mdocs-nofiles" >
          No files found in this folder.
        </p>
      </td>
    </tr>
  </table>
</div>