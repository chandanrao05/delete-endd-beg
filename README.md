# delete-end-beg
int deleteend()
{
  struct node *temp;
  temp=head;
  if(temp==NULL)
  {
    printf("no more elements to display");
  }
  elseif(temp->next==NULL)
  {
    printf("%d %s %s %s %f %d\n",temp1->ssn,temp1->name,temp1->dept,temp1->desg,temp1->sal,temp1->phno);
    free(temp1);
    head=NULL;
    retuen 0;
   }
   else
   {
    temp2=temp1->prev;
    temp2->next=NULL;
    printf("%d %s %s %s %f %d\n",temp1->ssn,temp1->name,temp1->dept,temp1->desg,temp1->sal,temp1->phno);
    free(temp1);
    temp1=temp2;
   }
   count--;
   return 0;
  }
  int deletebeg()
  {
    struct node *temp;
     temp=head;
  if(temp==NULL)
  {
    printf("no more elements to display");
  }
  elseif(temp->next==NULL)
  {
    printf("%d %s %s %s %f %d\n",temp1->ssn,temp1->name,temp1->dept,temp1->desg,temp1->sal,temp1->phno);
    free(temp1);
    head=NULL;
    retuen 0;
   }
   else
   {
    head=head->next;
    printf("%d %s %s %s %f %d\n",temp1->ssn,temp1->name,temp1->dept,temp1->desg,temp1->sal,temp1->phno);
    free(temp);
   }
   count--;
   return 0;
